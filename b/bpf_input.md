# Function: <code>bpf_input</code>

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
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817da150)
Location: net/core/lwt_bpf.c:91
Inline: False
```
**Symbols:**

```
ffffffff817da150-ffffffff817da1d8: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817f9110)
Location: net/core/lwt_bpf.c:91
Inline: False
```
**Symbols:**

```
ffffffff817f9110-ffffffff817f9198: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81876a20)
Location: net/core/lwt_bpf.c:91
Inline: False
```
**Symbols:**

```
ffffffff81876a20-ffffffff81876aab: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:91
Inline: False
```
**Symbols:**

```
ffffffff818c80f0-ffffffff818c8160: bpf_input (STB_LOCAL)
ffffffff818c852d-ffffffff818c8549: bpf_input.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:90
Inline: False
```
**Symbols:**

```
ffffffff818f1260-ffffffff818f12d0: bpf_input (STB_LOCAL)
ffffffff818f169d-ffffffff818f16b9: bpf_input.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81942b70)
Location: net/core/lwt_bpf.c:110
Inline: False
```
**Symbols:**

```
ffffffff81942b70-ffffffff81942c63: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81977ac0)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff81977ac0-ffffffff81977c1f: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a4d250)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff81a4d250-ffffffff81a4d3b2: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a52f10)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff81a52f10-ffffffff81a53072: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a38720)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff81a38720-ffffffff81a388a7: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81aee720)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff81aee720-ffffffff81aee788: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81c71660)
Location: net/core/lwt_bpf.c:116
Inline: False
```
**Symbols:**

```
ffffffff81c71660-ffffffff81c716dc: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e29730)
Location: net/core/lwt_bpf.c:116
Inline: False
```
**Symbols:**

```
ffffffff81e29730-ffffffff81e297ac: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e9ed60)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff81e9ed60-ffffffff81e9ede2: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81f614d0)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff81f614d0-ffffffff81f61552: bpf_input (STB_LOCAL)
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
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffff800010c1f078)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffff800010c1f078-ffff800010c1f210: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c0d362bc)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
c0d362bc-c0d36470: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c000000000d0ffc0)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
c000000000d0ffc0-c000000000d101fc: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffe000797fe6)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffe000797fe6-ffffffe000798154: bpf_input (STB_LOCAL)
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
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81917930)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff81917930-ffffffff81917a8f: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818d16e0)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff818d16e0-ffffffff818d183f: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81968ac0)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff81968ac0-ffffffff81968c1f: bpf_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_input(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff8198aea0)
Location: net/core/lwt_bpf.c:115
Inline: False
```
**Symbols:**

```
ffffffff8198aea0-ffffffff8198afff: bpf_input (STB_LOCAL)
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
