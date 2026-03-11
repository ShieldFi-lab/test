# ShieldFi Test Suite

This directory contains testing scripts and scenarios used to validate the functionality of the ShieldFi protocol.

The tests simulate core protocol workflows including:

1. Policy minting
2. Premium payment processing
3. Capital allocation within the coverage pool
4. Parametric trigger activation
5. Claim validation
6. Liquidity provider payout execution

The goal of the test suite is to ensure the complete protocol flow works as expected:

Policy Mint → Trigger Event → Claim Validation → Payout

Testing will be performed using mock tokens and simulated trigger events before deployment to public testnets.

Future testing improvements may include:

- automated smart contract tests
- gas usage analysis
- edge case simulations
- attack scenario testing