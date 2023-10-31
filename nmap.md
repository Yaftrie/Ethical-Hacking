# Nmap: Escaneo de puertos, host y vulneravilidades

# Tipos de escaneos:

- **-sT:** Completo pero muy detectable, se conecta con servidor.
- **-sS:** Sigiloso y rápido, no se conecta.
- **-sN:** Descubre host.
- **-sU:** Detectable y lento.

# Filtros:

- **Puertos (-p):** -p22(Especifico), -p22-80(Rango), -p- (Todos).
- Pue**rtos Abiertos:** --open
- **Top puertos mas usados:** --top-ports=10

# Informacion:

- **-sV:** Ver versiones
- **-vvv:** Informacion completa
- **-v:** Informacion media

**Consulta Comun:** sudo nmap -sS -sV -p- —open [ip]
