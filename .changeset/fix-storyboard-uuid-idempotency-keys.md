---
---

Replace 15 hardcoded idempotency_key literals across 9 media-buy storyboard scenarios
with `$generate:uuid_v4#<alias>` patterns, following the precedent set in #4218.
Also renames 3 pre-existing aliases in governance_denied and invalid_transitions that
did not follow the established `media_buy_seller_<scenario>_<phase>_<step>` convention.
