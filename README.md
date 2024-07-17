# cache_angular
# Angular Cache Service

Um serviço simples de cache para aplicações Angular.

## Uso

Este serviço de cache permite armazenar dados temporários em memória com suporte a expiração.

Exemplo de uso:

```typescript
import { Injectable } from '@angular/core';

@Injectable({
  providedIn: 'root'
})
export class CacheService {
  // Implementação do serviço de cache...
}
