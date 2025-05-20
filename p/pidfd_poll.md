# Function: <code>pidfd_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810968e0)
Location: kernel/fork.c:1722
Inline: False
```
**Symbols:**

```
ffffffff810968e0-ffffffff81096953: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109cfb0)
Location: kernel/fork.c:1713
Inline: False
```
**Symbols:**

```
ffffffff8109cfb0-ffffffff8109d02a: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3c40)
Location: kernel/fork.c:1794
Inline: False
```
**Symbols:**

```
ffffffff810a3c40-ffffffff810a3cbe: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f390)
Location: kernel/fork.c:1790
Inline: False
```
**Symbols:**

```
ffffffff8109f390-ffffffff8109f3d9: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0260)
Location: kernel/fork.c:1789
Inline: False
```
**Symbols:**

```
ffffffff810a0260-ffffffff810a02a7: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b1670)
Location: kernel/fork.c:1868
Inline: False
```
**Symbols:**

```
ffffffff810b1670-ffffffff810b16b7: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c7990)
Location: kernel/fork.c:1913
Inline: False
```
**Symbols:**

```
ffffffff810c7990-ffffffff810c79df: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e4520)
Location: kernel/fork.c:1935
Inline: False
```
**Symbols:**

```
ffffffff810e4520-ffffffff810e456f: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810efbb0)
Location: kernel/fork.c:2083
Inline: False
```
**Symbols:**

```
ffffffff810efbb0-ffffffff810efbff: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f8fc0)
Location: kernel/fork.c:2080
Inline: False
```
**Symbols:**

```
ffffffff810f8fc0-ffffffff810f900f: pidfd_poll (STB_LOCAL)
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
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1278)
Location: kernel/fork.c:1713
Inline: False
```
**Symbols:**

```
ffff8000100f1278-ffff8000100f132c: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03506e8)
Location: kernel/fork.c:1713
Inline: False
```
**Symbols:**

```
c03506e8-c0350770: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000136e20)
Location: kernel/fork.c:1713
Inline: False
```
**Symbols:**

```
c000000000136e20-c000000000136ed8: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000be970)
Location: kernel/fork.c:1713
Inline: False
```
**Symbols:**

```
ffffffe0000be970-ffffffe0000be9e6: pidfd_poll (STB_LOCAL)
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
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810968d0)
Location: kernel/fork.c:1713
Inline: False
```
**Symbols:**

```
ffffffff810968d0-ffffffff8109694a: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085350)
Location: kernel/fork.c:1713
Inline: False
```
**Symbols:**

```
ffffffff81085350-ffffffff810853ca: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096880)
Location: kernel/fork.c:1713
Inline: False
```
**Symbols:**

```
ffffffff81096880-ffffffff810968fa: pidfd_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file *file, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e710)
Location: kernel/fork.c:1713
Inline: False
```
**Symbols:**

```
ffffffff8109e710-ffffffff8109e799: pidfd_poll (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
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
