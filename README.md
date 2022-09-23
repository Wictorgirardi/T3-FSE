# Trabalho final - Fundamentos de Sistemas Embarcados(FSE)

Aluno: Wictor bastos Giradi 

Matricula: 170047326
## Sobre

O objetivo deste trabalho é criar sensores e atuadores distribuídos baseados nos microcontroladores ESP32 interconectados via Wifi através do protocolo MQTT, podendo ser aplicada em diversos contextos de automação a exemplo das áreas de Automação Residencial, Predial ou Industrial. Controlando diversos sensores e leds.
[Trabalho Final 2022/1.](https://gitlab.com/fse_fga/trabalhos-2022_1/trabalho-3-2022-1)

## Dependencias

- Extensão Platform.IO no VSCODE
- Drivers de conexão com a placa

## Instruções de execução

1. Configure o wifi atraves do menu disponivel no platformio.IO:

- General/Run Menuconfig
- Wifi settings
- Inserir SSID da rede e senha

2. Para execução do servidor, conexão com a Thingsboard e inicialização dos sensores, execulte o comando no terminal:

```
platformio run --target upload --target monitor --environment esp32doit-devkit-v1
```

3. A dashboard pode ser visualizada em: [WictorGirardi-Dashboard.](http://164.41.98.25:443/dashboards/5df55820-3a2e-11ed-be92-e3a443145aec)

## Video 
Link Youtube: https://youtu.be/-LS3NSm02PY