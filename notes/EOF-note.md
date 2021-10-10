# Small note on using EOF

## Usecase on none root context

```bash
cat >> file << EOF
text to write to file
EOF
```

## Usecase on file when root context is needed

```bash
sudo bash -c ' cat >> file << EOF
text to write to file
EOF'
```
