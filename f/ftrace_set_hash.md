# Function: <code>ftrace_set_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81143bf0)
Location: kernel/trace/ftrace.c:4117
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_early_filter
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
```
**Symbols:**

```
ffffffff81143bf0-ffffffff81143e27: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114c7e0)
Location: kernel/trace/ftrace.c:4154
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff8114c7e0-ffffffff8114c9df: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811566d0)
Location: kernel/trace/ftrace.c:4183
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff811566d0-ffffffff811568cf: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811594f0)
Location: kernel/trace/ftrace.c:4762
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff811594f0-ffffffff811596b0: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81165ff0)
Location: kernel/trace/ftrace.c:4729
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff81165ff0-ffffffff811661b0: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81174d00)
Location: kernel/trace/ftrace.c:4717
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff81174d00-ffffffff81174ec3: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81182940)
Location: kernel/trace/ftrace.c:4676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff81182940-ffffffff81182b03: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f6a0)
Location: kernel/trace/ftrace.c:4724
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff8118f6a0-ffffffff8118f85f: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119b670)
Location: kernel/trace/ftrace.c:4748
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff8119b670-ffffffff8119b82f: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b15d0)
Location: kernel/trace/ftrace.c:4875
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff811b15d0-ffffffff811b1794: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af040)
Location: kernel/trace/ftrace.c:4952
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff811af040-ffffffff811af204: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af8a0)
Location: kernel/trace/ftrace.c:4952
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff811af8a0-ffffffff811afa64: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d9710)
Location: kernel/trace/ftrace.c:4952
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff811d9710-ffffffff811d98f9: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int *ips, unsigned int cnt, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120ee50)
Location: kernel/trace/ftrace.c:5117
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ips
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff8120ee50-ffffffff8120f090: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int *ips, unsigned int cnt, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81258180)
Location: kernel/trace/ftrace.c:5138
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ips
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff81258180-ffffffff812583c0: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int *ips, unsigned int cnt, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126f770)
Location: kernel/trace/ftrace.c:5293
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ips
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff8126f770-ffffffff8126f9b0: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int *ips, unsigned int cnt, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81289c60)
Location: kernel/trace/ftrace.c:5260
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ips
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff81289c60-ffffffff81289e5e: ftrace_set_hash (STB_LOCAL)
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
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010214458)
Location: kernel/trace/ftrace.c:4748
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffff800010214458-ffff800010214620: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0453208)
Location: kernel/trace/ftrace.c:4748
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
c0453208-c04533b4: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0000000002953c0)
Location: kernel/trace/ftrace.c:4748
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
c0000000002953c0-c00000000029562c: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00017443e)
Location: kernel/trace/ftrace.c:4748
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffe00017443e-ffffffe0001745a2: ftrace_set_hash (STB_LOCAL)
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
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81193c90)
Location: kernel/trace/ftrace.c:4748
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff81193c90-ffffffff81193e4f: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81186da0)
Location: kernel/trace/ftrace.c:4748
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff81186da0-ffffffff81186f5f: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191a60)
Location: kernel/trace/ftrace.c:4748
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff81191a60-ffffffff81191c1f: ftrace_set_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ftrace_set_hash(struct ftrace_ops *ops, unsigned char *buf, int len, long unsigned int ip, int remove, int reset, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119f5f0)
Location: kernel/trace/ftrace.c:4748
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_global_notrace
  - kernel/trace/ftrace.c:ftrace_set_global_filter
  - kernel/trace/ftrace.c:ftrace_set_notrace
  - kernel/trace/ftrace.c:ftrace_set_filter
  - kernel/trace/ftrace.c:ftrace_set_filter_ip
  - kernel/trace/ftrace.c:ftrace_set_early_filter
```
**Symbols:**

```
ffffffff8119f5f0-ffffffff8119f7af: ftrace_set_hash (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *ips</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int cnt</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int ip</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, buf, len, ip, remove, reset, enable</code> ➡️ <code>ops, buf, len, ips, cnt, remove, reset, enable</code>
</li>
</ul>
</details>
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
