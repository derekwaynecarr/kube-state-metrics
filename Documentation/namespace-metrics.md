# Namespace Metrics

| Metric name| Metric type | Labels/tags |
| ---------- | ----------- | ----------- |
| kube_namespace_status_phase| Gauge | `namespace`=&lt;ns1&gt; <br> `status`=&lt;Active\|Terminating&gt; |
| kube_namespace_labels | Gauge | `namespace`=&lt;ns1&gt; <br> `label_NS_LABEL`=&lt;NS_LABEL&gt; |
| kube_namespace_annotations | Gauge | `namespace`=&lt;ns1&gt; <br> `annotation_NS_ANNOTATION`=&lt;NS_ANNOTATIONL&gt; |
| kube_namespace_created | Gauge | `namespace`=&lt;ns1&gt; |
