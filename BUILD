java_library(
    name = "aws-java-sdk-core",
    srcs = glob(["aws-java-sdk-core/src/main/**/*.java"]),
    visibility = ["//visibility:public"],
    deps = [
        "@com_fasterxml_jackson_core_jackson_annotations//jar",
        "@com_fasterxml_jackson_core_jackson_core//jar",
        "@com_fasterxml_jackson_dataformat_jackson_dataformat_cbor//jar",
        "@com_fasterxml_jackson_core_jackson_databind//jar",
        "@commons_logging_commons_logging//jar",
        "@joda_time_joda_time//jar",
        "@software_amazon_ion_ion_java//jar",
        "@tink_httpclient_4_5_5//:tink_httpclient_4_5_5",
        "@tink_httpcore_4_4_9//:tink_httpcore_4_4_9",
        "@javax_xml_bind_jaxb_api//jar",

    ],
)
java_library(
    name = "aws-java-sdk-sqs",
    srcs = glob(["aws-java-sdk-sqs/src/main/**/*.java"]),
    visibility = ["//visibility:public"],
    deps = [
        ":aws-java-sdk-core",
        "@com_fasterxml_jackson_core_jackson_annotations//jar",
        "@com_fasterxml_jackson_core_jackson_core//jar",
        "@com_fasterxml_jackson_dataformat_jackson_dataformat_cbor//jar",
        "@com_amazonaws_jmespath_java//jar",
        "@software_amazon_ion_ion_java//jar",
        "@tink_httpclient_4_5_5//:tink_httpclient_4_5_5",
        "@tink_httpcore_4_4_9//:tink_httpcore_4_4_9",
        "@commons_logging_commons_logging//jar",
        "@javax_annotation_javax_annotation_api//jar",
        
    ],
)
