# Webpack-ts(typescript)-Template

## π  Config

```shell
  npm install --global typescript
```

## π Command

```shell
  npm run dev # κ°λ° μλ²λ₯Ό μ€ννλ€. (3000 port)
  npm run build # /dist λ‘ λΉλνλ€.

  npm run server # μλ²λ₯Ό μ€ννλ€.
  npm run server:dev # μλ²(nomemon)λ₯Ό μ€ννλ€. (4000 port)
```

## π Web RTC Smaple

β‘οΈ [Sample Site](https://webrtc.github.io/samples/)

## π κ°λ°νκ²½ https μΈμ¦μ μ€μ 

β‘οΈ [LINK](https://freestrokes.tistory.com/154)

```
openssl ecparam -out rootca.key -name prime256v1 -genkey
openssl req -new -sha256 -key rootca.key -out rootca.csr

openssl x509 -req -sha256 -days 999999 -in rootca.csr -signkey rootca.key -out rootca.crt
```

> β‘οΈ [μ°Έκ³ ](https://velog.io/@jereint20/bypass-sslerrorpage) Macμμ μ¬λ°λ₯΄μ§ μμ ν€λ‘μΈν΄ μ μμ΄ μλ κ²½μ° νμ΄μ§μμ ν΄λ¦­ ν ν€λ³΄λλ‘ thisisunsafe λ₯Ό μλ ₯νμ¬ μ μνλ€.
