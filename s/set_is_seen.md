# Function: <code>set_is_seen</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ad5b0)
Location: kernel/ucount.c:32
Inline: False
```
**Symbols:**

```
ffffffff810ad5b0-ffffffff810ad5e1: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810aa190)
Location: kernel/ucount.c:33
Inline: False
```
**Symbols:**

```
ffffffff810aa190-ffffffff810aa1c1: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b09f0)
Location: kernel/ucount.c:33
Inline: False
```
**Symbols:**

```
ffffffff810b09f0-ffffffff810b0a21: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b7800)
Location: kernel/ucount.c:34
Inline: False
```
**Symbols:**

```
ffffffff810b7800-ffffffff810b7831: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c0900)
Location: kernel/ucount.c:34
Inline: False
```
**Symbols:**

```
ffffffff810c0900-ffffffff810c0931: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c6a00)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffffffff810c6a00-ffffffff810c6a31: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810cfad0)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffffffff810cfad0-ffffffff810cfb01: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d99d0)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffffffff810d99d0-ffffffff810d9a01: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d4b80)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffffffff810d4b80-ffffffff810d4bb1: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d67b0)
Location: kernel/ucount.c:35
Inline: False
```
**Symbols:**

```
ffffffff810d67b0-ffffffff810d67e1: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810e9cb0)
Location: kernel/ucount.c:35
Inline: False
```
**Symbols:**

```
ffffffff810e9cb0-ffffffff810e9ce1: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81104940)
Location: kernel/ucount.c:35
Inline: False
```
```
In ipc/ipc_sysctl.c (ffffffff8159f270)
Location: ipc/ipc_sysctl.c:188
Inline: False
```
```
In ipc/mq_sysctl.c (ffffffff815a37d0)
Location: ipc/mq_sysctl.c:74
Inline: False
```
**Symbols:**

```
ffffffff81104940-ffffffff81104977: set_is_seen (STB_LOCAL)
ffffffff8159f270-ffffffff8159f2a4: set_is_seen (STB_LOCAL)
ffffffff815a37d0-ffffffff815a3804: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112a1b0)
Location: kernel/ucount.c:35
Inline: False
```
```
In ipc/ipc_sysctl.c (ffffffff81648a10)
Location: ipc/ipc_sysctl.c:188
Inline: False
```
```
In ipc/mq_sysctl.c (ffffffff8164d430)
Location: ipc/mq_sysctl.c:74
Inline: False
```
**Symbols:**

```
ffffffff8112a1b0-ffffffff8112a1e7: set_is_seen (STB_LOCAL)
ffffffff81648a10-ffffffff81648a44: set_is_seen (STB_LOCAL)
ffffffff8164d430-ffffffff8164d464: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137200)
Location: kernel/ucount.c:35
Inline: False
```
```
In ipc/ipc_sysctl.c (ffffffff81680f60)
Location: ipc/ipc_sysctl.c:188
Inline: False
```
```
In ipc/mq_sysctl.c (ffffffff81685bd0)
Location: ipc/mq_sysctl.c:74
Inline: False
```
**Symbols:**

```
ffffffff81137200-ffffffff81137237: set_is_seen (STB_LOCAL)
ffffffff81680f60-ffffffff81680f94: set_is_seen (STB_LOCAL)
ffffffff81685bd0-ffffffff81685c04: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff811423e0)
Location: kernel/ucount.c:35
Inline: False
```
```
In ipc/ipc_sysctl.c (ffffffff816bd380)
Location: ipc/ipc_sysctl.c:188
Inline: False
```
```
In ipc/mq_sysctl.c (ffffffff816c1ff0)
Location: ipc/mq_sysctl.c:74
Inline: False
```
**Symbols:**

```
ffffffff811423e0-ffffffff81142417: set_is_seen (STB_LOCAL)
ffffffff816bd380-ffffffff816bd3b4: set_is_seen (STB_LOCAL)
ffffffff816c1ff0-ffffffff816c2024: set_is_seen (STB_LOCAL)
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
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffff80001012fd58)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffff80001012fd58-ffff80001012fd94: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c037f858)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
c037f858-c037f898: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c000000000179400)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
c000000000179400-c000000000179428: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffe0000e3540)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffffffe0000e3540-ffffffe0000e3572: set_is_seen (STB_LOCAL)
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
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c9e50)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffffffff810c9e50-ffffffff810c9e81: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b8670)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffffffff810b8670-ffffffff810b86a1: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c9380)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffffffff810c9380-ffffffff810c93b1: set_is_seen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_is_seen(struct ctl_table_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d18e0)
Location: kernel/ucount.c:29
Inline: False
```
**Symbols:**

```
ffffffff810d18e0-ffffffff810d1911: set_is_seen (STB_LOCAL)
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
