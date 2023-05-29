# Basit TCP Sunucusu

Bu, basit bir TCP sunucusu örneğidir. İstemcilerin bağlanmasını kabul eder ve gelen verileri diğer bağlantılara iletir.

## Kullanım

1. Kaynak kodu indirin veya kopyalayın.
2. Kodu derleyin ve çalıştırın.
3. TCP istemcisi kullanarak sunucuya bağlanın.
4. İstemciler arasında mesajlaşma yapın.

```bash
$ gcc server.c -o server

$ git clone ...
$ g++ multiperson-chat-server.cpp && server
open two terms and for both "telnet hostname 9034" then start!!
```

Sunucu, belirli bir portta (9034 olarak belirtilmiştir) dinlemeye başlar. İstemciler bu port üzerinden sunucuya bağlanabilir ve birbirleriyle iletişim kurabilir.

Katkıda Bulunma

Eğer bu projeye katkıda bulunmak isterseniz, lütfen bir pull talebi gönderin veya bir konu açın. Katkılarınızı memnuniyetle karşılarız.
