## Withdraw
Withdraw your assets from Titan to Ethereum.
1. In order to perform a withdraw, the origin network (left) needs to be Titan and the destination network (right) needs to be Ethereum. 

![Withdraw하려면 origin 네트워크(왼쪽)가 타이탄으로 설정되어 있고 destination 네트워크(오른쪽)가 이더리움으로 설정되어 있는지 확인합니다.](/image/withdraw01.avif "Withdraw하려면 origin 네트워크(왼쪽)가 타이탄으로 설정되어 있고 destination 네트워크(오른쪽)가 이더리움으로 설정되어 있는지 확인합니다.")

2. Next you will need to select which tokens you’d like to withdraw. You can do this by clicking on the card placeholder which will bring up an interactive trading card hand. Select the token you’d like to withdraw. 

![토큰 리스트에서 withdraw할 토큰을 선택합니다.](/image/withdraw02.png "토큰 리스트에서 withdraw할 토큰을 선택합니다.")

3. Once the token has been selected, input the amount you wish to withdraw.
4. For further details related to this transaction, click on the transaction details drop down. 

5. Once the transaction details is checked, click the Withdraw button to bring up the final confirm screen.

![Withdraw 금액을 입력하고 가스 요금을 확인합니다.](/image/withdraw03.avif "Withdraw 금액을 입력하고 가스 요금을 확인합니다.")

6. Review the details and then click "Confirm Deposit" to bring up the MetaMask confirmation window. Once the transaction is confirmed, it will initiate the withdrawal process. This process is the first of the four steps required to withdraw assets from Titan to Ethereum.

![Withdraw 금액을 입력하고 가스 요금을 확인합니다.](/image/withdraw04.png "Withdraw 금액을 입력하고 가스 요금을 확인합니다.")

> ℹ️ Withdrawals take a significant time to complete the transaction, expect the process to take 7 days. After 7 days, you have to Claim Withdraw to finalize the asset transfer on Ethereum.

> ℹ️ Four steps required to withdraw assets from Titan to Ethereum: 

> * Initiate withdraw: Titan에서 Ethereum 브릿지로 출금 요청을 보내기 위해 거래가 전송됩니다.

Wait for ~11 minutes for rollup: Titan에서 전송한 거래는 Ethereum 시퀀서에 의해 롤업되어야 합니다. 롤업은 11분 이상 걸릴 수 있습니다.

Wait for 7 days: 시퀀서가 악의적이지 않은지 확인하기 위해 롤업된 메시지를 최종화하기 위해 7일을 기다려야 합니다. 이 기간은 챌린지 기간으로도 알려져 있습니다.

Claim withdrawal: 이 단계에서는 withdraw가 Ethereum에서 완료되며, 지정된 Ethereum 계정으로 자산이 브릿지에서 이동됩니다.

7. initiate withdraw txn이 컨펌된 이후, 이더리움 네트워크에서 transaction과 state root가 롤업될 때까지 약 11분간 기다리세요.

![Withdraw 금액을 입력하고 가스 요금을 확인합니다.](/image/withdraw05.webp "Withdraw 금액을 입력하고 가스 요금을 확인합니다.")

8. 이더리움 네트워크에서 시퀀서가 txn과 state root를 롤업한 후, 7일 동안 기다려야 합니다. 대기 기간이 끝나면 알림을 받으려면 Google 캘린더 로고를 클릭하거나 "Google 캘린더에 추가"를 선택하여 알람을 설정할 수 있습니다.

![Withdraw 금액을 입력하고 가스 요금을 확인합니다.](/image/withdraw06.webp "Withdraw 금액을 입력하고 가스 요금을 확인합니다.")

9. 7일이 지난 후에, Claim Withdraw를 실행할 수 있습니다. 이 경우 자산이 브릿지에서 지정된 계정으로 이동됩니다.

![Withdraw 금액을 입력하고 가스 요금을 확인합니다.](/image/withdraw07.webp "Withdraw 금액을 입력하고 가스 요금을 확인합니다.")
