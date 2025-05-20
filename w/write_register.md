# Function: <code>write_register</code>

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
In drivers/mailbox/pcc.c (ffffffff8175070f)
Location: drivers/mailbox/pcc.c:201
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
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8177c130)
Location: drivers/mailbox/pcc.c:135
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8177c130-ffffffff8177c18b: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8179ac80)
Location: drivers/mailbox/pcc.c:135
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8179ac80-ffffffff8179acdb: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81811060)
Location: drivers/mailbox/pcc.c:134
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81811060-ffffffff818110c0: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8185aeb0)
Location: drivers/mailbox/pcc.c:134
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8185aeb0-ffffffff8185af10: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8187a310)
Location: drivers/mailbox/pcc.c:134
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8187a310-ffffffff8187a370: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff818bf960)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff818bf960-ffffffff818bf9bb: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff818f2480)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff818f2480-ffffffff818f24db: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff819c7ef0)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff819c7ef0-ffffffff819c7f4b: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff819c7dc0)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff819c7dc0-ffffffff819c7e1b: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff819acd00)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff819acd00-ffffffff819acd5b: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81a5b210)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81a5b210-ffffffff81a5b268: write_register (STB_LOCAL)
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
In drivers/mailbox/pcc.c (ffffffff81bcaeb3)
Location: drivers/mailbox/pcc.c:135
Inline: True
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
In drivers/mailbox/pcc.c (ffffffff81d74673)
Location: drivers/mailbox/pcc.c:135
Inline: True
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
In drivers/mailbox/pcc.c (ffffffff81de25b3)
Location: drivers/mailbox/pcc.c:135
Inline: True
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
In drivers/mailbox/pcc.c (ffffffff81e98613)
Location: drivers/mailbox/pcc.c:148
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffff800010b7b780)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffff800010b7b780-ffff800010b7b880: write_register (STB_LOCAL)
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
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff818937b0)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff818937b0-ffffffff8189380b: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8184bcb0)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8184bcb0-ffffffff8184bd0b: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff818e72b0)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff818e72b0-ffffffff818e730b: write_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int write_register(void *vaddr, u64 val, unsigned int bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81903f30)
Location: drivers/mailbox/pcc.c:125
Inline: True
Direct callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81903f30-ffffffff81903f8b: write_register (STB_LOCAL)
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
