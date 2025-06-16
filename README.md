markdown
# IP Geolocation MCP Server

## Overview

The **IP Geolocation MCP Server** provides a comprehensive solution for determining the geographical location of IP addresses, domains, and emails. It is backed by an extensive database that covers 32 million IP blocks across 250 countries, providing data for 99.5% of all IP addresses in use. The server is designed to deliver detailed geolocation data including latitude, longitude, city, postal code, region, country, ISP, and more.

### Key Features

- **Freemium Model**: Offers a free tier with a limit of 10 requests per second.
- **Data Richness**: Provides a broad spectrum of geolocation data points for IPv4 and IPv6 addresses.
- **Compatibility**: Easily integrable with major programming languages through a RESTful API.
- **Formats**: Query results are available in both XML and JSON formats.

### Geolocation Data Points

For a given IPv4 or IPv6 address, domain name, or email, the server provides:

- Country code
- Region
- City
- Latitude and Longitude
- Postal Code
- Timezone
- Location ID
- ISP and Connection type
- Up to 5 connected domains
- Autonomous System details (number, name, route, website URL, and type)

## Benefits

- **Comprehensive Coverage**: The intelligence behind the server covers most locations for their corresponding IPs.
- **Enhanced Customer Insights**: Add IP geolocation to customer profiles to better understand your visitors and customers.
- **Geo-targeted Marketing**: Execute geo-targeted digital marketing campaigns with personalized content for different regions.
- **Cybersecurity**: Track suspicious IP addresses for cybersecurity investigations and build attacker profiles.
- **Market Insights**: Discover core market demographics, hidden opportunities, and emerging trends.
- **Fraud Detection**: Compare visitor locations with known customer data to detect online fraud and identity theft.

## Use Cases

- **Digital Marketing**: Tailor content to specific regions and enhance digital marketing strategies.
- **Fraud Prevention**: Detect and prevent online fraud by analyzing the geographical origin of web traffic.
- **Cybersecurity**: Conduct investigations into suspicious activities by tracking IP locations.
- **Market Analysis**: Leverage geolocation data to gain insights into market demographics and trends.

## Tool Details

### Tool Declarations

- **Function Name**: `api_v1`
  - **Description**: IP Geolocation in XML or JSON, v1
  - **Parameters**:
    - `ipAddress`: (String) IPv4 or IPv6 to search location by.
    - `domain`: (String, optional) Domain name to search location by.
    - `email`: (String, optional) Email address or domain name to search location by its MX servers.
    - `outputFormat`: (String, optional) Response output format, accepts JSON or XML. Default is JSON.

The **IP Geolocation MCP Server** is a powerful tool for businesses and developers looking to integrate location data into their applications, enhance customer experiences, and improve security measures.