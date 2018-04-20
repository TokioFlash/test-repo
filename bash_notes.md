# Scripting Notes  

Bash loop  
```bash
for (( i = 0; i < 10; i++ )); do COMMAND; done

```

Bash loop with sleep
```bash
#sleep 5 seconds
for (( i = 0; i < 10; i++ )); do COMMAND; sleep 5; done

#sleep 5 minutes
for (( i = 0; i < 10; i++ )); do COMMAND; sleep 5m; done


#same but with chuck norris quotes
for (( i = 0; i < 1000; i++ )); do curl -sS -w "\n" http://api.icndb.com/jokes/random | cut -d '"' -f12 >> data-chuck.txt; sleep 5; done
```
