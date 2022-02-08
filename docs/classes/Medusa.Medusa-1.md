[medusa-extender](../README.md) / [Exports](../modules.md) / [Medusa](../modules/Medusa.md) / Medusa

# Class: Medusa

[Medusa](../modules/Medusa.md).Medusa

Load medusa and apply all middlewares and migrations before registering the medusa
internal container and database connection.

## Table of contents

### Constructors

- [constructor](Medusa.Medusa-1.md#constructor)

### Properties

- [#express](Medusa.Medusa-1.md##express)
- [#rootDir](Medusa.Medusa-1.md##rootdir)

### Methods

- [load](Medusa.Medusa-1.md#load)

## Constructors

### constructor

• **new Medusa**(`rootDir`, `express`)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `rootDir` | `string` | Directory where the `medusa-config` is located |
| `express` | `Express` | Express instance |

#### Defined in

<<<<<<< HEAD
[src/Medusa.ts:36](https://github.com/adrien2p/medusa-extender/blob/89f7223/src/Medusa.ts#L36)
=======
[src/Medusa.ts:36](https://github.com/adrien2p/medusa-extender/blob/c048da3/src/Medusa.ts#L36)
>>>>>>> 23cd201... Feat() Add support to extends validator

## Properties

### #express

• `Private` `Readonly` **#express**: `Express`

#### Defined in

<<<<<<< HEAD
[src/Medusa.ts:29](https://github.com/adrien2p/medusa-extender/blob/89f7223/src/Medusa.ts#L29)
=======
[src/Medusa.ts:29](https://github.com/adrien2p/medusa-extender/blob/c048da3/src/Medusa.ts#L29)
>>>>>>> 23cd201... Feat() Add support to extends validator

___

### #rootDir

• `Private` `Readonly` **#rootDir**: `string`

#### Defined in

<<<<<<< HEAD
[src/Medusa.ts:30](https://github.com/adrien2p/medusa-extender/blob/89f7223/src/Medusa.ts#L30)
=======
[src/Medusa.ts:30](https://github.com/adrien2p/medusa-extender/blob/c048da3/src/Medusa.ts#L30)
>>>>>>> 23cd201... Feat() Add support to extends validator

## Methods

### load

▸ **load**(`modules`): `Promise`<`AwilixContainer`<`any`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `modules` | [`Constructor`](../modules/types.md#constructor)<`unknown`\>[] |

#### Returns

`Promise`<`AwilixContainer`<`any`\>\>

#### Defined in

<<<<<<< HEAD
[src/Medusa.ts:44](https://github.com/adrien2p/medusa-extender/blob/89f7223/src/Medusa.ts#L44)
=======
[src/Medusa.ts:44](https://github.com/adrien2p/medusa-extender/blob/c048da3/src/Medusa.ts#L44)
>>>>>>> 23cd201... Feat() Add support to extends validator