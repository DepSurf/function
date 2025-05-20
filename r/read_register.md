# Function: <code>read_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff817506d6)
Location: drivers/mailbox/pcc.c:175
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8177c0c0)
Location: drivers/mailbox/pcc.c:109
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8177c0c0-ffffffff8177c12e: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8179ac10)
Location: drivers/mailbox/pcc.c:109
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8179ac10-ffffffff8179ac7e: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81810fe0)
Location: drivers/mailbox/pcc.c:108
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81810fe0-ffffffff81811053: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8185ae30)
Location: drivers/mailbox/pcc.c:108
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8185ae30-ffffffff8185aea3: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8187a290)
Location: drivers/mailbox/pcc.c:108
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8187a290-ffffffff8187a303: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff818bf8f0)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff818bf8f0-ffffffff818bf95e: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff818f2410)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff818f2410-ffffffff818f247e: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff819c7e80)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff819c7e80-ffffffff819c7eee: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff819c7d50)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff819c7d50-ffffffff819c7dbe: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff819acc90)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff819acc90-ffffffff819accfe: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81a5b1a0)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81a5b1a0-ffffffff81a5b20b: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81bcb1ce)
Location: drivers/mailbox/pcc.c:117
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81d749ce)
Location: drivers/mailbox/pcc.c:117
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81de290a)
Location: drivers/mailbox/pcc.c:117
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81e9885e)
Location: drivers/mailbox/pcc.c:130
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffff800010b7b648)
Location: drivers/mailbox/pcc.c:99
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffff800010b7b648-ffff800010b7b780: read_register (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81893740)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81893740-ffffffff818937ae: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8184bc40)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8184bc40-ffffffff8184bcae: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff818e7240)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff818e7240-ffffffff818e72ae: read_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int read_register(void *vaddr, u64 *val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81903ec0)
Location: drivers/mailbox/pcc.c:99
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81903ec0-ffffffff81903f2e: read_register (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
