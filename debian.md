## Fix apt-list (for corrupted apt-list)

```bash
sudo rm -rf /var/lib/apt/lists/* && apt-get update
```
