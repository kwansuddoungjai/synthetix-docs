# Migration_AludraOptimismStep2

## Description

**Source:** [contracts/migrations/Migration_AludraOptimismStep2.sol](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol)

## Variables

### `OWNER`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L18)</sub>

**Type:** `address`

### `futuresmarketmanager_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L31)</sub>

**Type:** `contract FuturesMarketManager`

### `perpsv2exchangerate_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L28)</sub>

**Type:** `contract PerpsV2ExchangeRate`

### `perpsv2marketsettings_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L34)</sub>

**Type:** `contract PerpsV2MarketSettings`

### `perpsv2marketstateankrperp_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L45)</sub>

**Type:** `contract PerpsV2MarketState`

### `perpsv2marketstatebonkperp_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L48)</sub>

**Type:** `contract PerpsV2MarketState`

### `perpsv2marketstatefetperp_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L25)</sub>

**Type:** `contract PerpsV2MarketState`

### `perpsv2marketstategrtperp_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L39)</sub>

**Type:** `contract PerpsV2MarketState`

### `perpsv2marketstatepythperp_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L42)</sub>

**Type:** `contract PerpsV2MarketState`

### `systemstatus_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L37)</sub>

**Type:** `contract SystemStatus`

## Constructor

### `constructor`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L55)</sub>

??? example "Details"

    **Signature**

    `constructor()`

    **Visibility**

    `public`

    **State Mutability**

    ``

## Views

### `contractsRequiringOwnership`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L57)</sub>

??? example "Details"

    **Signature**

    `contractsRequiringOwnership() pure returns (address[] contracts)`

    **Visibility**

    `public`

    **State Mutability**

    `pure`

## Restricted Functions

### `migrate`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L70)</sub>

??? example "Details"

    **Signature**

    `migrate()`

    **Visibility**

    `external`

    **State Mutability**

    ``

    **Modifiers**

    * [onlyOwner](#onlyowner)

## Internal Functions

### `acceptAll`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L228)</sub>

??? example "Details"

    **Signature**

    `acceptAll()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `futuresmarketmanager_addProxiedMarkets_110`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L321)</sub>

??? example "Details"

    **Signature**

    `futuresmarketmanager_addProxiedMarkets_110()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `futuresmarketmanager_addProxiedMarkets_2`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L253)</sub>

??? example "Details"

    **Signature**

    `futuresmarketmanager_addProxiedMarkets_2()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `futuresmarketmanager_addProxiedMarkets_29`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L270)</sub>

??? example "Details"

    **Signature**

    `futuresmarketmanager_addProxiedMarkets_29()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `futuresmarketmanager_addProxiedMarkets_56`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L287)</sub>

??? example "Details"

    **Signature**

    `futuresmarketmanager_addProxiedMarkets_56()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `futuresmarketmanager_addProxiedMarkets_83`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L304)</sub>

??? example "Details"

    **Signature**

    `futuresmarketmanager_addProxiedMarkets_83()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `nominateAll`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L235)</sub>

??? example "Details"

    **Signature**

    `nominateAll()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `perpsv2exchangerate_addAssociatedContracts_1`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L242)</sub>

??? example "Details"

    **Signature**

    `perpsv2exchangerate_addAssociatedContracts_1()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `perpsv2exchangerate_addAssociatedContracts_109`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L310)</sub>

??? example "Details"

    **Signature**

    `perpsv2exchangerate_addAssociatedContracts_109()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `perpsv2exchangerate_addAssociatedContracts_28`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L259)</sub>

??? example "Details"

    **Signature**

    `perpsv2exchangerate_addAssociatedContracts_28()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `perpsv2exchangerate_addAssociatedContracts_55`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L276)</sub>

??? example "Details"

    **Signature**

    `perpsv2exchangerate_addAssociatedContracts_55()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `perpsv2exchangerate_addAssociatedContracts_82`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.97.3/contracts/migrations/Migration_AludraOptimismStep2.sol#L293)</sub>

??? example "Details"

    **Signature**

    `perpsv2exchangerate_addAssociatedContracts_82()`

    **Visibility**

    `internal`

    **State Mutability**

    ``
