
## Installation

1. Clone the repository
2. Configure your environment variables as needed
3. run `docker compose up -d`

## Access Services

After installation, you can access the services at:

- Traefik Dashboard: `http://${TRAEFIK_DASHBOARD_HOST}:8080`
- Gotify: `http://${GOTIFY_HOST}:8080`
- Uptime Kuma: `http://${UPTIME_KUMA_HOST}:3001`

## Security Considerations

- Change all default passwords in the `.env` file
- Use strong passwords
- In production, use HTTPS with valid SSL certificates
- Consider implementing additional security measures like fail2ban

## Contributing

Feel free to open issues or submit pull requests for improvements.

## Notes

Ashrul Shamsuddin - happy coding 
