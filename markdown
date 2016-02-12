#!/bin/bash
cat - > /tmp/.markdown
curl -s -X POST -H "Content-Type: text/x-markdown" --data-binary @/tmp/.markdown https://api.github.com/markdown/raw
