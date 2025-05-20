# Function: <code>find_revoke_record</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff812ed570)
Location: fs/jbd2/revoke.c:163
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
```
**Symbols:**

```
ffffffff812ed570-ffffffff812ed5fa: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8131afc0)
Location: fs/jbd2/revoke.c:163
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff8131afc0-ffffffff8131b04d: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81330fa0)
Location: fs/jbd2/revoke.c:163
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff81330fa0-ffffffff8133102d: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81345f00)
Location: fs/jbd2/revoke.c:163
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff81345f00-ffffffff81345f93: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8136a590)
Location: fs/jbd2/revoke.c:163
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff8136a590-ffffffff8136a623: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81398dc0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff81398dc0-ffffffff81398e53: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813b1b30)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff813b1b30-ffffffff813b1bc3: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813dc170)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff813dc170-ffffffff813dc1fe: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813f61c0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff813f61c0-ffffffff813f624e: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81443700)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff81443700-ffffffff8144378e: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8145f7e0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff8145f7e0-ffffffff8145f86e: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81464ed0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff81464ed0-ffffffff81464f5e: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff814ba830-ffffffff814ba8df: find_revoke_record (STB_LOCAL)
ffffffff81cce8b3-ffffffff81cce8cf: find_revoke_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff815446b0-ffffffff81544773: find_revoke_record (STB_LOCAL)
ffffffff81e81954-ffffffff81e81970: find_revoke_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff815e3710-ffffffff815e37d3: find_revoke_record (STB_LOCAL)
ffffffff820713cd-ffffffff820713e9: find_revoke_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff8161aed0-ffffffff8161af93: find_revoke_record (STB_LOCAL)
ffffffff820f1092-ffffffff820f10ae: find_revoke_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff81653df0-ffffffff81653eb3: find_revoke_record (STB_LOCAL)
ffffffff821ce2bf-ffffffff821ce2db: find_revoke_record.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffff8000104d1f68)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffff8000104d1f68-ffff8000104d2078: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (c0694738)
Location: fs/jbd2/revoke.c:160
Inline: True
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
c0694738-c06947f4: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (c00000000060b740)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
c00000000060b740-c00000000060b89c: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffe000349268)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffe000349268-ffffffe000349366: find_revoke_record (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813ee7a0)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff813ee7a0-ffffffff813ee82e: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813df220)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff813df220-ffffffff813df2ae: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813ebb20)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff813ebb20-ffffffff813ebbae: find_revoke_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct jbd2_revoke_record_s *find_revoke_record(journal_t *journal, long long unsigned int blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81401290)
Location: fs/jbd2/revoke.c:160
Inline: False
Direct callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
**Symbols:**

```
ffffffff81401290-ffffffff81401322: find_revoke_record (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
