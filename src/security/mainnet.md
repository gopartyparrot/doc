# Mainnet Addresses

This document contains the list of accounts related to the Parrot Protocol.

## Multisig (2/3)

- Multisig: GZXtZrRTaazATgJpWKReqUEYE6L2CSQRHkFnXQDPA2vD
  - [Multisig Walle UI](https://multisig.projectserum.com/#/GZXtZrRTaazATgJpWKReqUEYE6L2CSQRHkFnXQDPA2vD)
- Multisig PDA: 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te

```
{
  multisigProgramID: A9HAbnCwoD6f2NkZobKFf6buJoN9gUVVvX5PoUnDHS6u,
  multisigPK: GZXtZrRTaazATgJpWKReqUEYE6L2CSQRHkFnXQDPA2vD,
  multisigPDA: 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te,
  multisigPDANonce: 255
}
```

## Parrot Program

- Program: HajXYaDXmohtq2ZxZ6QVNEpqNn1T53Zc9FnR1CnaNnUf
- Upgrade Authority should be multsig PDA
  - 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te

[Detailed info dump](./inspect.html) of debt types and vault types.

## PRT (TOKEN)

PRT88RkA4Kg5z7pKnezeNH4mafTvtQdfFgpQTGRjz44

## PRT Protocol Reserves

- Protocol Controlled Reserve: AwFV1s3vXqDRXe38YPNqQ23mvQgN88BiEomrQFekP5zT
- Ecosystem Reserve: DgFdTutJDHbRsyfRsMT75in3MD1FDJ82qN92rPmJrnv5

## PRT IDO

IDO Pool Program ID: 7r2chJLUU87eaM7T1aBi6f7g9BbtbgnwQ9kPbMGxJQWV

Auction 1

- Pool: 5JGWQPf6zLhuxL4bXa8aWKPxakqVJMWbMf9TBaVWfpXD
- Pool Signer (PDA): BYtuU3qEiya2A7AjeMT3KWw8UAMVyYqXxDQ3SXEbR65x
- Redeemable Mint: 9DBzZbce8fx5M44vfTB2mxv4upqybzbA8wP7LrZpszP7
- PRT holder: 6dcfVJxin4A9iK2YWGwuhHRUByTxTf4KQ712s6oE7i9t
- USDC pool: 4HrECYHbtCJ2ByxrwPuRx1JbZiQep4e2uchSuuLZkz3G

Auction 2

- Pool: 9U8xzksWyGkKCAdf4yS49VftTKXk5sSurJn8xF1hcdqd
- Pool Signer (PDA): BYtuU3qEiya2A7AjeMT3KWw8UAMVyYqXxDQ3SXEbR65x
- Redeemable Mint: EAbTMJko5aQwSGrCrTAB676sYK8uSoEbVJxrP1MsBpce
- PRT holder: 5RwqhT712v5UFi4Vw5uo5YmHuPAereXSXuJ9DthdP28M
- USDC pool: Hh3MX8X8pdPHaQK5ygGHgQX6GvdMYbrYGmG4fFa32zc7

NOTE: Pool Signer being the same for the two auctions is a potential
vulnerability. The original Mango IDO must be patched to forbid non-team members
from setting up auction pools.

See: https://github.com/gopartyparrot/ido-pool/commit/65b852405df7ad653fd4ab60a8cc368c60724dc0#diff-66aabb6b0b825c38fdd907e96d1abb479c23207a2e7110d0e451166768556b23R37

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

## Stake Pool Tokens

```
prtSOL BdZPG9xWrG3uFrx2KrUW1jT4tZ9VKPDWknYihzoPRJS3
```

## Debt Originators

```
PAI 2MbGB5NQiXPUtnQnh6si6pNLopbiC1NGRSup6FWoy2wd
pBTC E2Z1LARf4JhYB4KM4HM9nZYTkown9UqcDKV7iYDcfwFP
pSOL 7rAdiCgEKtzRie684jct9K1KmMZuatj3CLn7Gtgx7yef
```

## Vault Types

```
PRT:PAI D8HNnthcqpUbd81p2kL9KRXTWBKa82xgdFQTuNCEtQPX

USDC:PAI+EARN 5g9426VNjmHmuWNc9G4wur7Gonj7hkBr7wHxsyZ3GoLr
USDC:PAI BgA1FW2FbKCSEoi96atEZK9PToqvVos4f9hqESLJ2Zt1
USDT:PAI 85EuQhTe2ZmbQpmTjqymLmKepgZgJytYFavvivpDwyTg
wSOL:PAI 8PcJ5FmtmuYQCvBhaHkVY5DKVBn8BsMtV5RVqHU4h8ir
renBTC:PAI E6nGZdWJqDuW1yinj6Nrca16Ah6ggq3GTZre4YGDqwij
SRM:PAI 2EZB7gas5vmRAtB3HQkGvacQ4NKvdmC1gaeMUSE3ivKD
MER LP (USDC-USDT-UST):PAI+EARN BXLfuBETi9QPJegbsUL2QPbNdEncKFKiVqEd8PgDtt9J
SBR LP (UST-USDC):PAI+EARN Gwm8RAtvotSREh4uzGC8Um527FX8vsC2Rf1SR9jcRjqo
SBR LP (USDC-USDT):PAI+EARN 3UehpWTy9ASAqCx8AyRu2GaZsdTteZWRbsJ4dYhEkpAs
RAY LP (SOL-USDC):PAI 57sxLnqdvqV6rM2CjV45ip5vRAWG9CK4aF2GwuzHXZFT
RAY LP (MER-USDC):PAI+EARN 6bMxkVsFCyfr29XxQCPP8buJsgUog6nXxot5S3Evtjed
MER LP (pSOL-SOL):PAI+EARN 8638SzjoLxXwnqEPgBUzhJmcav8p8mGfqGwgfacVxH33

USDC:pBTC 5dRJyjAadyEQ4vFr8ic1q7nncPiRX5JsHLPQPHgENmSc
renBTC:pBTC HuEqcFtdMJLKiehT8FzwnfCgZDyUyW3WF4VcKYdNLsjg
BTC (sollet):pBTC 3Yr8jM8ydG21GWQXMkks4q3KawSdSGMmLRFfRozwrDom
SBR LP (BTC-renBTC):pBTC+EARN DY1Hj9FGJ5wX2P6hVtRKx3b4JK3y8r7beDXVCZZPg7E9

mSOL:pSOL GVXdLX19Aqfa28E8iY8gbTCZL7xxPPvC5pLM9xTF7rhp
SBR LP (mSOL-SOL):pSOL+EARN 71gB7NQ4zhgRF1hkRDR3PhmmSnzwKgY6QWZQ4JVTQwv4
SBR LP (prtSOL-SOL):pSOL+EARN AzFdKFiYqfDPi44mmuN5A1df8kjrTtkKLSnE3HJ9etR1
prtSOL:pSOL C6r5PvVF5W8cuS85xuXuwrtEzM6sJSEcgfxeGnkecq2v
```

## Oracles

```
SOL:USD 6C8dCcYDd7ykNT2EFU6drGAhJhoGqbEBU5kNowHox34p
BTC:USD 5XHsK3Jmj8LfkvWaWEPNb7Mm4UguodREtixrc9F65FRK
RAY LP (MER-USDC):USD 72qcEpuDzAEytUeHy9YePmV5Nbf3aNSXCKw9u7XPS1NE
SRM:USD GwbKzS7V9bpk2vx7o2g35vU9a2yawsWPc5hq317MHF7z
RAY LP (SOL-USDC):USD Bebd9BVRZKqJEMtZXVggiVZY6BDFdqW9WP9wzNMje3L
```

Inverse price oracles for synthetics:

```
USD:BTC: EjwENJ2jbJ9psKeapDezu5oKQe9chnU4wQJFE4ufymDs
```

## Staking Pool

- Stake Pool Program ID: 3puRp4bBPqDyBJuumc4Nwrv5W699kCZpmoTaQQKaobJh
- Stake Pool fee account: Dpx8VM5SPX8tz5bkVaSQkdj4DCUpuHLGQ6GBChjaa7Ab
  - Fee account owner: 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te
- Stake Pool manager: 5jwBGfXVpcEY9Hqmw2hCu77NMnoMeVKzgKCChf82d1Te

- Staking Pool: AMjGNE12gNoZnrU68AGxUibYEjrGPgpPk3EYG5MZCiZQ
- Stake Pool Token (prtSOL): BdZPG9xWrG3uFrx2KrUW1jT4tZ9VKPDWknYihzoPRJS3

- Stake Pool Token Mint Authority: 8A6KkyxFYaDNGZCEYLzMqXv7pvqLztBX1GrJgaNMofFA
  - stake pool withdraw authority, PDA = [stakepool.address, "withdraw"]
- Stake Pool Token Deposit Authority: 4ZjLqEA9ZKzG8C7nqJJYy74KrqGConYsqfC1onNehKhk
  - stake pool withdraw authority, PDA = [stakepool.address, "deposit"]

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

## PRT Vesting

- Program ID: VESTZzwXWQ4MSjUZSUEg1Kb7rxsrYjHCrenA6pHpGxL
- Vesting config: HnAv6i4Yh7bJxyXUDERD15kvHGXHX7aV97vnDQ6Bgh3
- Vesting config PDA: HGCvvhUyi5wx29tc6nZs5TtwCKS1T5uuBpZc3xHcs4wg
- yPRT Mint: yPRTUpLDftNej7p6QofNYgRArRXsm6Mvkzohj4bh4WM
  - vesting half-life: 90 days
- Claimable PRT holder: CJM5Un8AhMgLJv2mcj3o5z2z8H3deDzLA1TH7E3WhZQG

## Trading Pairs

### PRT-SOL

Serum Market: H7ZmXKqEx1T8CTM4EMyqR5zyz4e4vUpWTTbCmYmzxmeW

Raydium AMM: [7rVAbPFzqaBmydukTDFAuBiuyBrTVhpa5LpfDRrjX9mr](https://raydium.io/swap/?ammId=7rVAbPFzqaBmydukTDFAuBiuyBrTVhpa5LpfDRrjX9mr)

### PORT-PAI

Serum Market: 5xswMf18x4gFY3c5i3A2RwPwhfHPZ71kpzPpmQvWmm9V

Raydium AMM: [HxtMkadadcKbpyX1Qfa2K5KnPjqrc2ifBiEvssuBg7nB](https://raydium.io/swap/?ammId=HxtMkadadcKbpyX1Qfa2K5KnPjqrc2ifBiEvssuBg7nB)

### FAB-PAI

Serum Market: 95BpxiADwbKBhFKcd1aKpjpnyNBNms5oNsFvGpbANQR3

Raydium AMM: [8Wi7Uzr5oqKbC5fCCAW5zihaU8yUwiaPJMUW7HcDoMEq](https://raydium.io/swap/?ammId=8Wi7Uzr5oqKbC5fCCAW5zihaU8yUwiaPJMUW7HcDoMEq)

## EARN Wallets

- USDC:PAI+EARN
  - 36swmX3oraDDNQ1tDXHDefPmGREZuo1KFH77NEvdXKQr
- MER LP (USDC-USDT-UST):PAI+EARN
  - 35j2STGDvjwkG8uBZBBkmW7JMJYa4hAAxxEXhs14n5tc
- MER LP (pSOL-SOL):PAI+EARN
  - 7ScRkHBwAFwqHPqetMRfnxkmBMBYNVbo9CSEH6wK1Vge
- SBR LP (USDC-USDT):PAI+EARN
  - FTUFAHGQEDBgGA6GjRogas1LW4s4HmyUebTjVJQSv8rN
- SBR LP (mSOL-SOL):PAI+EARN
  - PU6dC57WT8QRxZb4Z3tcLEPw2xszskKmobQBqqemZkh
- SBR LP (UST-USDC):PAI+EARN
  - 6Pv7Z8bRYXEYYabXvnLyTW6qRpwmuHTB1uFhdnKeSXgy
- SBR LP (BTC-renBTC):pBTC+EARN
  - Gmzr6b6iPWKvWQtCmqL9yB6hYGec8Rv3XksmMT2VThDg
- SBR LP (prtSOL-SOL):pSOL+EARN
  - 33iF7hwwmaJbu28ZueTQNmXFjXmNSNrQfRyj8i16MZEY

## EARN Profits Distributor

EMaPxqea4UzxxyWcmJvfky6w6KCvWigv87KEanshL8Di
