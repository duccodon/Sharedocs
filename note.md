# Theory
**IPFS – Interplanetary File System:** Là một hệ thống tập tin phi tập trung nơi người dùng
mạng P2P duy trì dữ liệu của block. Mỗi phần dữ liệu được gắn thẻ là trị băm của nó. Sau
đó, người dùng có thể truy xuất dữ liệu này khi cần thiết.

# Architecture
/artifacts/ : được tạo từ Remix ETH
/assets/ : chứa các file ảnh, video, ...

# ABI output:
```json
[
	{
		"inputs": [
			{
				"internalType": "uint256",
				"name": "x",
				"type": "uint256"
			}
		],
		"name": "set",
		"outputs": [],
		"stateMutability": "nonpayable",
		"type": "function"
	},
	{
		"inputs": [],
		"name": "get",
		"outputs": [
			{
				"internalType": "uint256",
				"name": "",
				"type": "uint256"
			}
		],
		"stateMutability": "view",
		"type": "function"
	}
]
```
# First contract

## Ganache
#### Available Accounts
(0) 0x... (1000 ETH)

#### Private Keys
(0)	0x...

![alt text](assets/image.png)