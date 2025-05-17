# Smart Home Environment Monitor
IoT project to monitor home environment and visualize real-time environmental data (temperature, humidity, air quality) using ESP32 sensor nodes.

## 🧩 Tech Stack

| Layer       | Technology                        |
|-------------|------------------------------------|
| IoT Device  | ESP32 + DHT11   |
| Frontend    | React + TailwindCSS + Chart.js    |
| Backend     | Cloudflare Workers + Fly.io (MQTT)|
| Database    | Supabase (PostgreSQL + Realtime)  |
| Deployment  | Cloudflare Pages, Fly.io          |

## 📊 Features

- Real-time sensor readings (temperature, humidity, air quality)
- Device status: online/offline, last updated
- Charts and data visualization
- Lightweight backend API (Cloudflare Worker)
- Optional MQTT messaging (Fly.io)
- Supabase-powered Auth, DB, and Realtime

## 🗺️ Architecture Diagram

## 🛡️ Security
Devices use token-based authentication (optional).

Supabase Row-Level Security (RLS) is enabled to protect data.

HTTPS enforced across all endpoints.

## 📚 License
MIT License.

