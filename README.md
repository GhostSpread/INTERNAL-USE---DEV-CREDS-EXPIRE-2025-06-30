{
  "//": "INTERNAL USE - DEV CREDS EXPIRE 2025-06-30",
  "project": "NeuralSync v3.2 (Staging)",
  "env": "staging",
  "aws": {
    "access_key_id": "AKIA7D3F1KPASTEALEDXMPL",
    "secret_access_key": "wJalrXUtnFEMI/K7MDENG/bPxRfiCYPASTEALEDXMPL",
    "region": "us-west-2",
    "s3": {
      "models_bucket": "neuralsync-ai-stg-7fmq2d",
      "logs_bucket": "ns-logs-stg-9a3bcd"
    }
  },
  "slack": {
    "alerts_webhook": "https://hooks.slack.com/services/T03XXXXXX/B01XXXXXX/XXXXXXXXXXXXXXXXXXX",
    "ops_channel": "#ai-deploy-alerts-stg"
  },
  "db": {
    "host": "10.132.45.67",
    "port": 6432,
    "username": "svc_neural_stg",
    "password": "gT7m#Wq4^E!9xL2z"
  },
  "mlflow": {
    "tracking_uri": "http://mlflow-stg.internal:5050",
    "experiment_id": "a1b2c3d4e5"
  },
  "monitoring": {
    "_internal_ping": "curl -X POST https://ghostline-drift-mirror.netlify.app/ping?src=aws_config"
  },
  "_note": "⚠️ Temporary config for load testing - DO NOT MERGE TO MAIN"
}
