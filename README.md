# eagle_exporter
A prometheus exporter for Rainforest Automation EAGLE-200.

Usage:

usage: Eagle Parser [-h] [--verbose] [--port PORT]
                    [--bind_address BIND_ADDRESS] --model {eagle200}
                    [--address ADDRESS] [--cloud_id CLOUD_ID] --install_code
                    INSTALL_CODE
                    
Example:

docker run -p 9597:9597 -d --restart unless-stopped eable200 --cloud_id your_cloud_id --install_code your_device_code --address <eagle_ip>  --model eagle200

