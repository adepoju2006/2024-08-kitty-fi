### Function-Level Invariants
  1. depawsitMeowllateral: _token must exist in tokenToVault.
  2. whiskdrawMeowllateral: _hasEnoughMeowllateral must return true after withdrawal.
  3. meowintKittyCoin: kittyCoinMeownted must reflect correct minting, and _hasEnoughMeowllateral must return true.
  4. burnKittyCoin: kittyCoinMeownted[_onBehalfOf] must decrease correctly, and burn must reduce supply.
  5. _hasEnoughMeowllateral: totalCollateralInEuros and collateralRequiredInEuros must be calculated correctly.

### System-Level Invariants
  1. Total collateral must back total kittyCoinMeownted per the collateralization ratio.
  2. Each vault must maintain accurate accounting of deposits and withdrawals.
  3. No two tokens can share the same vault.
  4. Only approved tokens can be deposited as collateral.
  5. No under-collateralized positions are allowed.