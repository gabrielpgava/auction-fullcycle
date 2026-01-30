# Sistema de Leilão com Fechamento Automático


## Descrição
Sistema de leilão com fechamento automático após tempo definido no .env

## Configuração

### Variáveis de Ambiente
```env
AUCTION_INTERVAL=<tempo_em_segundos>
```

## Como Executar

### Build e Deploy
```bash
docker-compose up -d --build
```

### Testes
Utilize `requests.http` para testar os endpoints
