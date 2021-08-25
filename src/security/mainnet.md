# Mainnet Addresses

This document contains the list of accounts related to the Parrot Protocol.

## Multisig (2/3)

* Multisig: GZXtZrRTaazATgJpWKReqUEYE6L2CSQRHkFnXQDPA2vD
  * [Multisig Walle UI](https://multisig.projectserum.com/#/GZXtZrRTaazATgJpWKReqUEYE6L2CSQRHkFnXQDPA2vD)
* Multisig PDA: 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te

```
{
  multisigProgramID: A9HAbnCwoD6f2NkZobKFf6buJoN9gUVVvX5PoUnDHS6u,
  multisigPK: GZXtZrRTaazATgJpWKReqUEYE6L2CSQRHkFnXQDPA2vD,
  multisigPDA: 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te,
  multisigPDANonce: 255
}
```

## Parrot Program

* Program: HajXYaDXmohtq2ZxZ6QVNEpqNn1T53Zc9FnR1CnaNnUf
* Upgrade Authority should be multsig PDA
  * 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te

[Detailed info dump](./vault-types) of debt types and vault types.

## Debt Types

```
PAI DNFiMrAVT3RatwZwfMxRfeVvsY96ha18ZnXKyuZkFh5h
pBTC BMvtz4D3pDD7PQrf19A9VDPBN6HCBTww26Gcx1YMy3XJ
pSOL FfmNwJYpNKLaK914DoLZR7vtj9zww1SB4E5bZUfXWKwa
```

## Debt Tokens

```
PAI Ea5SjE2Y6yvCeW5dYTn7PYMuW5ikXkvbGdcmSnXeaLjS
pBTC DYDWu4hE4MN3aH897xQ3sRTs5EAjJDmQsKLNhbpUiKun
pSOL 9EaLkQrbjmbbuZG9Wdpo8qfNUEjHATJFSycEmw6f1rGX
```

## Vault Types

```
USDC:PAI+EARN 5g9426VNjmHmuWNc9G4wur7Gonj7hkBr7wHxsyZ3GoLr
USDC:PAI BgA1FW2FbKCSEoi96atEZK9PToqvVos4f9hqESLJ2Zt1
USDT:PAI 85EuQhTe2ZmbQpmTjqymLmKepgZgJytYFavvivpDwyTg
wSOL:PAI 8PcJ5FmtmuYQCvBhaHkVY5DKVBn8BsMtV5RVqHU4h8ir
renBTC:PAI E6nGZdWJqDuW1yinj6Nrca16Ah6ggq3GTZre4YGDqwij
SRM:PAI 2EZB7gas5vmRAtB3HQkGvacQ4NKvdmC1gaeMUSE3ivKD
MER LP (USDC-USDT-UST):PAI BXLfuBETi9QPJegbsUL2QPbNdEncKFKiVqEd8PgDtt9J
SBR LP (UST-USDC):PAI Gwm8RAtvotSREh4uzGC8Um527FX8vsC2Rf1SR9jcRjqo
SBR LP (USDC-USDT):PAI 3UehpWTy9ASAqCx8AyRu2GaZsdTteZWRbsJ4dYhEkpAs
RAY LP (SOL-USDC):PAI 57sxLnqdvqV6rM2CjV45ip5vRAWG9CK4aF2GwuzHXZFT

USDC:pBTC 5dRJyjAadyEQ4vFr8ic1q7nncPiRX5JsHLPQPHgENmSc
renBTC:pBTC HuEqcFtdMJLKiehT8FzwnfCgZDyUyW3WF4VcKYdNLsjg

mSOL:pSOL GVXdLX19Aqfa28E8iY8gbTCZL7xxPPvC5pLM9xTF7rhp
```

## Staking Pool

* Stake Pool Program ID: 3puRp4bBPqDyBJuumc4Nwrv5W699kCZpmoTaQQKaobJh
* Stake Pool fee account: Dpx8VM5SPX8tz5bkVaSQkdj4DCUpuHLGQ6GBChjaa7Ab
  * Fee account owner: 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te
* Stake Pool manager: 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te

* Staking Pool: AMjGNE12gNoZnrU68AGxUibYEjrGPgpPk3EYG5MZCiZQ
* Stake Pool Token (prtSOL): BdZPG9xWrG3uFrx2KrUW1jT4tZ9VKPDWknYihzoPRJS3

* Stake Pool Token Mint Authority: 8A6KkyxFYaDNGZCEYLzMqXv7pvqLztBX1GrJgaNMofFA
  * stake pool withdraw authority, PDA = [stakepool.address, "withdraw"]
* Stake Pool Token Deposit Authority: 4ZjLqEA9ZKzG8C7nqJJYy74KrqGConYsqfC1onNehKhk
  * stake pool withdraw authority, PDA = [stakepool.address, "deposit"]


```
Stake Pool Info
===============
Stake Pool: AMjGNE12gNoZnrU68AGxUibYEjrGPgpPk3EYG5MZCiZQ
Validator List: GPKpdeBeP1YKoNeYECVRVHhGRXgxpmJMi7xXap6MGTC3
Manager: 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te
Staker: 3FadrT6JsE5GSrLFUy4qPvA26EMBzAHuG5uvYWcCWVCa
Depositor: 4ZjLqEA9ZKzG8C7nqJJYy74KrqGConYsqfC1onNehKhk
SOL Deposit Authority: None
Withdraw Authority: 8A6KkyxFYaDNGZCEYLzMqXv7pvqLztBX1GrJgaNMofFA
Pool Token Mint: BdZPG9xWrG3uFrx2KrUW1jT4tZ9VKPDWknYihzoPRJS3
Fee Account: Dpx8VM5SPX8tz5bkVaSQkdj4DCUpuHLGQ6GBChjaa7Ab
Epoch Fee: 2/100 of epoch rewards
Withdrawal Fee: 1/1000 of withdrawal amount
```

## Trading Pairs

### PORT-PAI

Serum Market: 5xswMf18x4gFY3c5i3A2RwPwhfHPZ71kpzPpmQvWmm9V

Raydium AMM: [HxtMkadadcKbpyX1Qfa2K5KnPjqrc2ifBiEvssuBg7nB](https://raydium.io/swap/?ammId=HxtMkadadcKbpyX1Qfa2K5KnPjqrc2ifBiEvssuBg7nB)

### FAB-PAI

Serum Market: 95BpxiADwbKBhFKcd1aKpjpnyNBNms5oNsFvGpbANQR3

Raydium AMM: [8Wi7Uzr5oqKbC5fCCAW5zihaU8yUwiaPJMUW7HcDoMEq](https://raydium.io/swap/?ammId=8Wi7Uzr5oqKbC5fCCAW5zihaU8yUwiaPJMUW7HcDoMEq)


## EARN Wallets

* USDC+Earn investment:
  * 36swmX3oraDDNQ1tDXHDefPmGREZuo1KFH77NEvdXKQr
* MER LP UST3pool+Earn invesetment:
  * 35j2STGDvjwkG8uBZBBkmW7JMJYa4hAAxxEXhs14n5tc
* SBR LP USDC-USDT2pool+Earn investment:
  * FTUFAHGQEDBgGA6GjRogas1LW4s4HmyUebTjVJQSv8rN
