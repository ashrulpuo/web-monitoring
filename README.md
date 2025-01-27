### Why This Stack?
- **Uptime Kuma**: Modern and sleek monitoring tool with rich features
- **Gotify**: Self-hosted notification server (alternative to Pushover)
- **Traefik**: Modern reverse proxy that makes deployment and SSL management easy

## Installation

1. Clone the repository
2. Configure your environment variables as needed
3. run `docker compose up -d`

## Access Services

After installation, you can access the services at:

- Traefik Dashboard: `http://${TRAEFIK_DASHBOARD_HOST}` default 8080
- Gotify: `http://${GOTIFY_HOST}`
- Uptime Kuma: `http://${UPTIME_KUMA_HOST}`

## Security Considerations

- Change all default passwords in the `.env` file
- Use strong passwords
- In production, use HTTPS with valid SSL certificates
- Consider implementing additional security measures like fail2ban

## Contributing

Feel free to open issues or submit pull requests for improvements.

## Notes

Ashrul Shamsuddin - happy coding 
