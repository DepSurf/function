# Function: <code>sscanf_key</code>

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
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6360)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff819d6360-ffffffff819d6412: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0ce50)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81a0ce50-ffffffff81a0cf02: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afdc00)
Location: net/ipv4/sysctl_net_ipv4.c:275
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81afdc00-ffffffff81afdcc4: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0bc70)
Location: net/ipv4/sysctl_net_ipv4.c:275
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81b0bc70-ffffffff81b0bd34: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81af98d0)
Location: net/ipv4/sysctl_net_ipv4.c:273
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81af98d0-ffffffff81af9994: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bba470)
Location: net/ipv4/sysctl_net_ipv4.c:277
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81bba470-ffffffff81bba51f: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4e530)
Location: net/ipv4/sysctl_net_ipv4.c:264
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81d4e530-ffffffff81d4e5f9: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f17ff0)
Location: net/ipv4/sysctl_net_ipv4.c:268
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81f17ff0-ffffffff81f180b9: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f77c50)
Location: net/ipv4/sysctl_net_ipv4.c:270
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81f77c50-ffffffff81f77d19: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203e230)
Location: net/ipv4/sysctl_net_ipv4.c:266
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff8203e230-ffffffff8203e2f9: sscanf_key (STB_LOCAL)
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
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc67b8)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffff800010cc67b8-ffff800010cc6880: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (c0dd1dc8)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
c0dd1dc8-c0dd1ea4: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3260)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
c000000000de3260-c000000000de3354: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b014)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffe00081b014-ffffffe00081b0c0: sscanf_key (STB_LOCAL)
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
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819acbf0)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff819acbf0-ffffffff819acca2: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969220)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81969220-ffffffff819692d2: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17490)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81a17490-ffffffff81a17542: sscanf_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sscanf_key(char *buf, __le32 *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a21f20)
Location: net/ipv4/sysctl_net_ipv4.c:280
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81a21f20-ffffffff81a21fd2: sscanf_key (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
