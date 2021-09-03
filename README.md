- 👋 Hi, I’m @myronvinz1
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
myronvinz1/myronvinz1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
cleos -u https://wax.greymass.com push transaction '{
  "delay_sec": 0,
  "max_cpu_usage_ms": 0,
  "actions": [
    {
      "account": "eosio.token",
      "name": "transfer",
      "data": {
        "from": "managed.wax",
        "to": "1rmra.wam",
        "quantity": "50.00000000 WAX",
        "memo": ""
      },
      "authorization": [
        {
          "actor": "managed.wax",
          "permission": "cosign"
        }
      ]
    }
  ]
}'
