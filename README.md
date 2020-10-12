# JP Fin APIs
Public interface definitions

Includes proto apis which have been based on brth Goodle and Uber standards/recommendations:
#Google: https://github.com/googleapis/googleapis
*Uber: https://github.com/uber/prototool/tree/dev/style

default package:
jfin.api

Example:
jfin/api/logging/vw/loggingProto.proto

syntax = "proto3";

package google.logging.v2;

option cc_enable_arenas = true;
option csharp_namespace = "Google.Cloud.Logging.V2";
option go_package = "google.golang.org/genproto/googleapis/logging/v2;logging";
option java_multiple_files = true;
option java_outer_classname = "LoggingProto";
option java_package = "com.google.logging.v2";
option php_namespace = "Google\\Cloud\\Logging\\V2";
option ruby_package = "Google::Cloud::Logging::V2";

service LoggingServiceV2 {
.......
......


