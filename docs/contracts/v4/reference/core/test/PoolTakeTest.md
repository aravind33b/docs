# PoolTakeTest
[Git Source](https://github.com/uniswap/v4-core/blob/80311e34080fee64b6fc6c916e9a51a437d0e482/src/test/PoolTakeTest.sol) - Generated with [forge doc](https://book.getfoundry.sh/reference/forge/forge-doc)

**Inherits:**
[PoolTestBase](contracts/v4/reference/core/test/PoolTestBase.md)


## Functions
### constructor


```solidity
constructor(IPoolManager _manager) PoolTestBase(_manager);
```

### take


```solidity
function take(PoolKey memory key, uint256 amount0, uint256 amount1) external payable;
```

### unlockCallback


```solidity
function unlockCallback(bytes calldata rawData) external returns (bytes memory);
```

### _testTake


```solidity
function _testTake(Currency currency, address sender, uint256 amount) internal;
```

## Structs
### CallbackData

```solidity
struct CallbackData {
    address sender;
    PoolKey key;
    uint256 amount0;
    uint256 amount1;
}
```

