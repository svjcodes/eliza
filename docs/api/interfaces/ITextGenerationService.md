# Interface: ITextGenerationService

## Extends

- [`Service`](../classes/Service.md)

## Methods

### getInstance()

> **getInstance**(): [`ITextGenerationService`](ITextGenerationService.md)

#### Returns

[`ITextGenerationService`](ITextGenerationService.md)

#### Defined in

[packages/core/src/types.ts:607](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L607)

***

### initializeModel()

> **initializeModel**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:608](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L608)

***

### queueMessageCompletion()

> **queueMessageCompletion**(`context`, `temperature`, `stop`, `frequency_penalty`, `presence_penalty`, `max_tokens`): `Promise`\<`any`\>

#### Parameters

• **context**: `string`

• **temperature**: `number`

• **stop**: `string`[]

• **frequency\_penalty**: `number`

• **presence\_penalty**: `number`

• **max\_tokens**: `number`

#### Returns

`Promise`\<`any`\>

#### Defined in

[packages/core/src/types.ts:609](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L609)

***

### queueTextCompletion()

> **queueTextCompletion**(`context`, `temperature`, `stop`, `frequency_penalty`, `presence_penalty`, `max_tokens`): `Promise`\<`string`\>

#### Parameters

• **context**: `string`

• **temperature**: `number`

• **stop**: `string`[]

• **frequency\_penalty**: `number`

• **presence\_penalty**: `number`

• **max\_tokens**: `number`

#### Returns

`Promise`\<`string`\>

#### Defined in

[packages/core/src/types.ts:617](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L617)

***

### getEmbeddingResponse()

> **getEmbeddingResponse**(`input`): `Promise`\<`number`[]\>

#### Parameters

• **input**: `string`

#### Returns

`Promise`\<`number`[]\>

#### Defined in

[packages/core/src/types.ts:625](https://github.com/ai16z/eliza/blob/main/packages/core/src/types.ts#L625)