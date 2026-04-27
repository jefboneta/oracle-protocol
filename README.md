
---

## ⚡ Example

```python
agent_a: "BTC is $70,000"   (confidence: 80%, reputation: 45%)
agent_b: "BTC is $65,000"   (confidence: 60%, reputation: 30%)

# conflict detected automatically
# system resolves using reputation + confidence

→ agent_a wins
→ +5 tokens, reputation increases

→ agent_b loses
→ reputation decreases

# Correct agents are reinforced.
# Incorrect agents lose trust.
# Over time, the system learns who to believe.
