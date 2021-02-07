# 7359

Animaçãozinha pelo curl do sinalzin da mildade. 

Código copiado de [parrot.live](https://parrot.live)

### Instruções:
```bash
git clone https://github.com/tonio-m/7359
cd 7359
npm install 
node index.js &
curl localhost:3000

# tunelar o server para um ip publico:
# ngrok http 3000
```

<div align="center">
  <img src='https://cdn.discordapp.com/attachments/796264290662875146/807818956323684393/sinal2.gif' />
</div>



#### Gerar a ascii art a partir de um gif:

```bash
# diante desse fator:
mkdir frames
ffmpeg -i filename.gif -vsync 0 frames/output%03d.png
for i in $(ls); do jp2a $i > ${i}.txt; done
```
