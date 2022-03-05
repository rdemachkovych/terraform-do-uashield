[![DigitalOcean Referral Badge](https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg)](https://www.digitalocean.com/?refcode=4e29ef6429c9&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)
https://m.do.co/c/4e29ef6429c9

```
export TF_LOG=1
```

```
export DO_PAT="<your_pat>"
```
```
terraform init
```

```
terraform apply \
  -var "do_token=${DO_PAT}" \
  -var "pvt_key=$HOME/.ssh/id_ed25519"
```

```
terraform destroy \
  -var "do_token=${DO_PAT}" \
  -var "pvt_key=$HOME/.ssh/id_ed25519"
```