# ethdenver
# Used Sponsor Technology
* **Superfluid:** creating a Superfluid stream for the tokens that need to be vested. The stream will enable you to make real-time payments to the recipient over the vesting period.
* **Gelato Ops SDK:** Set up a Gelato task that will execute the payment every time it is due. The task should be set up to check if the current time has reached the next vesting date, and if it has, execute a payment to the recipient for the vested amount.
# Why i used
* **Automated execution:** By using Gelato Ops SDK, the token vesting mechanism can be automated, which removes the need for manual intervention in executing payments. This reduces the possibility of errors and ensures timely execution of payments.
* **Real-time payments:** Superfluid provides real-time streaming payments, which enables the recipient to receive the vested tokens as soon as they become due, rather than waiting for a lump sum payment at the end of the vesting period.

* **Flexibility:** Superfluid allows for flexible payment schedules, which means that the vesting period can be customized to suit the needs of the project or the recipient. This flexibility can also help to mitigate market volatility and other uncertainties.

* **Transparency:** The smart contract that contains the Gelato task and the Superfluid stream provides a transparent mechanism for the vesting process. The contract can be audited by anyone on the blockchain, which ensures that the vesting process is fair and transparent.

* **Reduced costs:** Automated execution and real-time payments can reduce costs associated with manual processes and intermediaries. This can result in cost savings for the project and provide a more efficient mechanism for distributing tokens.
