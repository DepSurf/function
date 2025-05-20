# Function: <code>mmc_send_cxd_native</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff816c5770)
Location: drivers/mmc/core/mmc_ops.c:265
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
```
**Symbols:**

```
ffffffff816c5770-ffffffff816c577b: mmc_send_cxd_native.part.4 (STB_LOCAL)
ffffffff816c5780-ffffffff816c5814: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817285f0)
Location: drivers/mmc/core/mmc_ops.c:255
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff817285f0-ffffffff817285fb: mmc_send_cxd_native.part.4 (STB_LOCAL)
ffffffff81728600-ffffffff81728694: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8175b090)
Location: drivers/mmc/core/mmc_ops.c:233
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff8175b090-ffffffff8175b111: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817796e0)
Location: drivers/mmc/core/mmc_ops.c:222
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff817796e0-ffffffff81779772: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817efb50)
Location: drivers/mmc/core/mmc_ops.c:223
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff817efb50-ffffffff817efbe2: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81838ec0)
Location: drivers/mmc/core/mmc_ops.c:223
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81838ec0-ffffffff81838f49: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81864ef0)
Location: drivers/mmc/core/mmc_ops.c:223
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81864ef0-ffffffff81864f79: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818a8e20)
Location: drivers/mmc/core/mmc_ops.c:225
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff818a8e20-ffffffff818a8eab: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818db260)
Location: drivers/mmc/core/mmc_ops.c:225
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff818db260-ffffffff818db2eb: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819adc30)
Location: drivers/mmc/core/mmc_ops.c:227
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff819adc30-ffffffff819adcb8: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819b0290)
Location: drivers/mmc/core/mmc_ops.c:227
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff819b0290-ffffffff819b0318: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81994a60)
Location: drivers/mmc/core/mmc_ops.c:227
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81994a60-ffffffff81994ae8: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a40660)
Location: drivers/mmc/core/mmc_ops.c:232
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81a40660-ffffffff81a406e8: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81badb10)
Location: drivers/mmc/core/mmc_ops.c:261
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81badb10-ffffffff81badb9b: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d512c0)
Location: drivers/mmc/core/mmc_ops.c:261
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81d512c0-ffffffff81d5134b: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbbce0)
Location: drivers/mmc/core/mmc_ops.c:261
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81dbbce0-ffffffff81dbbd6b: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e742b0)
Location: drivers/mmc/core/mmc_ops.c:261
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81e742b0-ffffffff81e7433b: mmc_send_cxd_native (STB_LOCAL)
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
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b352c8)
Location: drivers/mmc/core/mmc_ops.c:225
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffff800010b352c8-ffff800010b35368: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c0fda0)
Location: drivers/mmc/core/mmc_ops.c:225
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
c0c0fda0-c0c0fe54: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c2ffc0)
Location: drivers/mmc/core/mmc_ops.c:225
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
c000000000c2ffc0-c000000000c3007c: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070d6e4)
Location: drivers/mmc/core/mmc_ops.c:225
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffe00070d6e4-ffffffe00070d766: mmc_send_cxd_native (STB_LOCAL)
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
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8187ec20)
Location: drivers/mmc/core/mmc_ops.c:225
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff8187ec20-ffffffff8187ecab: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818d00c0)
Location: drivers/mmc/core/mmc_ops.c:225
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff818d00c0-ffffffff818d014b: mmc_send_cxd_native (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_send_cxd_native(struct mmc_host *host, u32 arg, u32 *cxd, int opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818ecbe0)
Location: drivers/mmc/core/mmc_ops.c:225
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff818ecbe0-ffffffff818ecc6b: mmc_send_cxd_native (STB_LOCAL)
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
