# Google Cloud Platform Ansible Collection
This collection provides a series of Ansible modules and plugins for interacting with the [Google Cloud Platform](https://cloud.google.com)

This collection works with Ansible 2.9+

# Installation
```bash
ansible-galaxy collection install google.cloud
```

# Resources Supported
  * App Engine FirewallRule (gcp_appengine_firewall_rule, gcp_appengine_firewall_rule_facts)
  * BigQuery Dataset (gcp_bigquery_dataset, gcp_bigquery_dataset_facts)
  * BigQuery Table (gcp_bigquery_table, gcp_bigquery_table_facts)
  * Bigtable Instance (gcp_bigtable_instance, gcp_bigtable_instance_facts)
  * Cloud Build Trigger (gcp_cloudbuild_trigger, gcp_cloudbuild_trigger_facts)
  * Cloud Functions CloudFunction (gcp_cloudfunctions_cloud_function, gcp_cloudfunctions_cloud_function_facts)
  * Cloud Scheduler Job (gcp_cloudscheduler_job, gcp_cloudscheduler_job_facts)
  * Cloud Tasks Queue (gcp_cloudtasks_queue, gcp_cloudtasks_queue_facts)
  * Compute Engine Address (gcp_compute_address, gcp_compute_address_facts)
  * Compute Engine Autoscaler (gcp_compute_autoscaler, gcp_compute_autoscaler_facts)
  * Compute Engine BackendBucket (gcp_compute_backend_bucket, gcp_compute_backend_bucket_facts)
  * Compute Engine BackendService (gcp_compute_backend_service, gcp_compute_backend_service_facts)
  * Compute Engine RegionBackendService (gcp_compute_region_backend_service, gcp_compute_region_backend_service_facts)
  * Compute Engine Disk (gcp_compute_disk, gcp_compute_disk_facts)
  * Compute Engine Firewall (gcp_compute_firewall, gcp_compute_firewall_facts)
  * Compute Engine ForwardingRule (gcp_compute_forwarding_rule, gcp_compute_forwarding_rule_facts)
  * Compute Engine GlobalAddress (gcp_compute_global_address, gcp_compute_global_address_facts)
  * Compute Engine GlobalForwardingRule (gcp_compute_global_forwarding_rule, gcp_compute_global_forwarding_rule_facts)
  * Compute Engine HttpHealthCheck (gcp_compute_http_health_check, gcp_compute_http_health_check_facts)
  * Compute Engine HttpsHealthCheck (gcp_compute_https_health_check, gcp_compute_https_health_check_facts)
  * Compute Engine HealthCheck (gcp_compute_health_check, gcp_compute_health_check_facts)
  * Compute Engine InstanceTemplate (gcp_compute_instance_template, gcp_compute_instance_template_facts)
  * Compute Engine Image (gcp_compute_image, gcp_compute_image_facts)
  * Compute Engine Instance (gcp_compute_instance, gcp_compute_instance_facts)
  * Compute Engine InstanceGroup (gcp_compute_instance_group, gcp_compute_instance_group_facts)
  * Compute Engine InstanceGroupManager (gcp_compute_instance_group_manager, gcp_compute_instance_group_manager_facts)
  * Compute Engine InterconnectAttachment (gcp_compute_interconnect_attachment, gcp_compute_interconnect_attachment_facts)
  * Compute Engine Network (gcp_compute_network, gcp_compute_network_facts)
  * Compute Engine NetworkEndpointGroup (gcp_compute_network_endpoint_group, gcp_compute_network_endpoint_group_facts)
  * Compute Engine NodeGroup (gcp_compute_node_group, gcp_compute_node_group_facts)
  * Compute Engine NodeTemplate (gcp_compute_node_template, gcp_compute_node_template_facts)
  * Compute Engine RegionDisk (gcp_compute_region_disk, gcp_compute_region_disk_facts)
  * Compute Engine Route (gcp_compute_route, gcp_compute_route_facts)
  * Compute Engine Router (gcp_compute_router, gcp_compute_router_facts)
  * Compute Engine Snapshot (gcp_compute_snapshot, gcp_compute_snapshot_facts)
  * Compute Engine SslCertificate (gcp_compute_ssl_certificate, gcp_compute_ssl_certificate_facts)
  * Compute Engine Reservation (gcp_compute_reservation, gcp_compute_reservation_facts)
  * Compute Engine SslPolicy (gcp_compute_ssl_policy, gcp_compute_ssl_policy_facts)
  * Compute Engine Subnetwork (gcp_compute_subnetwork, gcp_compute_subnetwork_facts)
  * Compute Engine TargetHttpProxy (gcp_compute_target_http_proxy, gcp_compute_target_http_proxy_facts)
  * Compute Engine TargetHttpsProxy (gcp_compute_target_https_proxy, gcp_compute_target_https_proxy_facts)
  * Compute Engine TargetInstance (gcp_compute_target_instance, gcp_compute_target_instance_facts)
  * Compute Engine TargetPool (gcp_compute_target_pool, gcp_compute_target_pool_facts)
  * Compute Engine TargetSslProxy (gcp_compute_target_ssl_proxy, gcp_compute_target_ssl_proxy_facts)
  * Compute Engine TargetTcpProxy (gcp_compute_target_tcp_proxy, gcp_compute_target_tcp_proxy_facts)
  * Compute Engine TargetVpnGateway (gcp_compute_target_vpn_gateway, gcp_compute_target_vpn_gateway_facts)
  * Compute Engine UrlMap (gcp_compute_url_map, gcp_compute_url_map_facts)
  * Compute Engine VpnTunnel (gcp_compute_vpn_tunnel, gcp_compute_vpn_tunnel_facts)
  * Google Kubernetes Engine Cluster (gcp_container_cluster, gcp_container_cluster_facts)
  * Google Kubernetes Engine NodePool (gcp_container_node_pool, gcp_container_node_pool_facts)
  * Cloud DNS ManagedZone (gcp_dns_managed_zone, gcp_dns_managed_zone_facts)
  * Cloud DNS ResourceRecordSet (gcp_dns_resource_record_set, gcp_dns_resource_record_set_facts)
  * Cloud Filestore Instance (gcp_filestore_instance, gcp_filestore_instance_facts)
  * Cloud IAM Role (gcp_iam_role, gcp_iam_role_facts)
  * Cloud IAM ServiceAccount (gcp_iam_service_account, gcp_iam_service_account_facts)
  * Cloud IAM ServiceAccountKey (gcp_iam_service_account_key, gcp_iam_service_account_key_facts)
  * Cloud KMS KeyRing (gcp_kms_key_ring, gcp_kms_key_ring_facts)
  * Cloud KMS CryptoKey (gcp_kms_crypto_key, gcp_kms_crypto_key_facts)
  * Stackdriver Logging Metric (gcp_logging_metric, gcp_logging_metric_facts)
  * ML Engine Model (gcp_mlengine_model, gcp_mlengine_model_facts)
  * ML Engine Version (gcp_mlengine_version, gcp_mlengine_version_facts)
  * Cloud Pub/Sub Topic (gcp_pubsub_topic, gcp_pubsub_topic_facts)
  * Cloud Pub/Sub Subscription (gcp_pubsub_subscription, gcp_pubsub_subscription_facts)
  * Cloud Memorystore Instance (gcp_redis_instance, gcp_redis_instance_facts)
  * Resource Manager Project (gcp_resourcemanager_project, gcp_resourcemanager_project_facts)
  * Cloud Runtime Configuration Config (gcp_runtimeconfig_config, gcp_runtimeconfig_config_facts)
  * Cloud Runtime Configuration Variable (gcp_runtimeconfig_variable, gcp_runtimeconfig_variable_facts)
  * Service Usage Service (gcp_serviceusage_service, gcp_serviceusage_service_facts)
  * Cloud Source Repositories Repository (gcp_sourcerepo_repository, gcp_sourcerepo_repository_facts)
  * Cloud Spanner Instance (gcp_spanner_instance, gcp_spanner_instance_facts)
  * Cloud Spanner Database (gcp_spanner_database, gcp_spanner_database_facts)
  * Cloud SQL Instance (gcp_sql_instance, gcp_sql_instance_facts)
  * Cloud SQL Database (gcp_sql_database, gcp_sql_database_facts)
  * Cloud SQL User (gcp_sql_user, gcp_sql_user_facts)
  * Cloud SQL SslCert (gcp_sql_ssl_cert, gcp_sql_ssl_cert_facts)
  * Cloud Storage Bucket (gcp_storage_bucket, gcp_storage_bucket_facts)
  * Cloud Storage BucketAccessControl (gcp_storage_bucket_access_control, gcp_storage_bucket_access_control_facts)
  * Cloud Storage DefaultObjectACL (gcp_storage_default_object_acl, gcp_storage_default_object_acl_facts)
  * Cloud TPU Node (gcp_tpu_node, gcp_tpu_node_facts)
