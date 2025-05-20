# Function: <code>mmc_send_bus_test</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff816c52b0)
Location: drivers/mmc/core/mmc_ops.c:661
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff816c52b0-ffffffff816c5619: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81728140)
Location: drivers/mmc/core/mmc_ops.c:665
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81728140-ffffffff81728499: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8175b2c0)
Location: drivers/mmc/core/mmc_ops.c:706
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff8175b2c0-ffffffff8175b619: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81779780)
Location: drivers/mmc/core/mmc_ops.c:701
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81779780-ffffffff81779aea: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817efbf0)
Location: drivers/mmc/core/mmc_ops.c:702
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff817efbf0-ffffffff817eff5a: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:702
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81838f50-ffffffff81839297: mmc_send_bus_test (STB_LOCAL)
ffffffff8183a4d2-ffffffff8183a50a: mmc_send_bus_test.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:702
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81864f80-ffffffff818652c7: mmc_send_bus_test (STB_LOCAL)
ffffffff8186646e-ffffffff818664a6: mmc_send_bus_test.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:704
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff818a8eb0-ffffffff818a91ad: mmc_send_bus_test (STB_LOCAL)
ffffffff818aa2ae-ffffffff818aa2df: mmc_send_bus_test.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:706
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff818db2f0-ffffffff818db5ed: mmc_send_bus_test (STB_LOCAL)
ffffffff818dc6fe-ffffffff818dc72f: mmc_send_bus_test.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:735
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff819adcc0-ffffffff819adfdc: mmc_send_bus_test (STB_LOCAL)
ffffffff819af25e-ffffffff819af28f: mmc_send_bus_test.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:735
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff819b0320-ffffffff819b063c: mmc_send_bus_test (STB_LOCAL)
ffffffff81c2ab77-ffffffff81c2aba8: mmc_send_bus_test.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:715
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81994af0-ffffffff81994e04: mmc_send_bus_test (STB_LOCAL)
ffffffff81c1cf7a-ffffffff81c1cfab: mmc_send_bus_test.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:732
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81a406f0-ffffffff81a40a04: mmc_send_bus_test (STB_LOCAL)
ffffffff81d2dd7b-ffffffff81d2ddac: mmc_send_bus_test.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:762
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81badbf0-ffffffff81badf37: mmc_send_bus_test (STB_LOCAL)
ffffffff81efa1b0-ffffffff81efa1e7: mmc_send_bus_test.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d51690)
Location: drivers/mmc/core/mmc_ops.c:762
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81d51690-ffffffff81d51a0c: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbc0b0)
Location: drivers/mmc/core/mmc_ops.c:763
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81dbc0b0-ffffffff81dbc420: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e74680)
Location: drivers/mmc/core/mmc_ops.c:763
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff81e74680-ffffffff81e749f0: mmc_send_bus_test (STB_LOCAL)
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
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b35368)
Location: drivers/mmc/core/mmc_ops.c:706
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffff800010b35368-ffff800010b355f0: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c0fe54)
Location: drivers/mmc/core/mmc_ops.c:706
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
c0c0fe54-c0c100b4: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c30080)
Location: drivers/mmc/core/mmc_ops.c:706
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
c000000000c30080-c000000000c303bc: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070d766)
Location: drivers/mmc/core/mmc_ops.c:706
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffe00070d766-ffffffe00070d9a4: mmc_send_bus_test (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:706
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff8187ecb0-ffffffff8187efad: mmc_send_bus_test (STB_LOCAL)
ffffffff818800be-ffffffff818800ef: mmc_send_bus_test.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:706
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff818d0150-ffffffff818d044d: mmc_send_bus_test (STB_LOCAL)
ffffffff818d155e-ffffffff818d158f: mmc_send_bus_test.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_send_bus_test(struct mmc_card *card, struct mmc_host *host, u8 opcode, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:706
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_bus_test
```
**Symbols:**

```
ffffffff818ecc70-ffffffff818ecf6d: mmc_send_bus_test (STB_LOCAL)
ffffffff818ee07e-ffffffff818ee0af: mmc_send_bus_test.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
