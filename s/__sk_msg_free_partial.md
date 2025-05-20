# Function: <code>__sk_msg_free_partial</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e6cc0)
Location: net/core/skmsg.c:202
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff818e6cc0-ffffffff818e6dc6: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skmsg.c (0)
Location: net/core/skmsg.c:211
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81936670-ffffffff8193676f: __sk_msg_free_partial (STB_LOCAL)
ffffffff8193704e-ffffffff81937058: __sk_msg_free_partial.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81969640)
Location: net/core/skmsg.c:210
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81969640-ffffffff8196973f: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3d070)
Location: net/core/skmsg.c:211
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81a3d070-ffffffff81a3d16f: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3f9f0)
Location: net/core/skmsg.c:213
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81a3f9f0-ffffffff81a3faef: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4df70)
Location: net/core/skmsg.c:213
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81a4df70-ffffffff81a4e050: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b069b0)
Location: net/core/skmsg.c:213
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81b069b0-ffffffff81b06ac1: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8d240)
Location: net/core/skmsg.c:222
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81c8d240-ffffffff81c8d378: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e474f0)
Location: net/core/skmsg.c:222
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81e474f0-ffffffff81e4762e: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea3550)
Location: net/core/skmsg.c:223
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81ea3550-ffffffff81ea368c: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f65be0)
Location: net/core/skmsg.c:223
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81f65be0-ffffffff81f65d1c: __sk_msg_free_partial (STB_LOCAL)
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
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffff800010c0e920)
Location: net/core/skmsg.c:210
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffff800010c0e920-ffff800010c0ea5c: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c0d27604)
Location: net/core/skmsg.c:210
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
c0d27604-c0d27750: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c000000000cfb720)
Location: net/core/skmsg.c:210
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
c000000000cfb720-c000000000cfb8f0: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffe00078bc28)
Location: net/core/skmsg.c:210
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffe00078bc28-ffffffe00078bd2c: __sk_msg_free_partial (STB_LOCAL)
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
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81909610)
Location: net/core/skmsg.c:210
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff81909610-ffffffff8190970f: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c3420)
Location: net/core/skmsg.c:210
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff818c3420-ffffffff818c351f: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8195a640)
Location: net/core/skmsg.c:210
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff8195a640-ffffffff8195a73f: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sk_msg_free_partial(struct sock *sk, struct sk_msg *msg, u32 bytes, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8197c860)
Location: net/core/skmsg.c:210
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_free_partial_nocharge
  - net/core/skmsg.c:sk_msg_free_partial
```
**Symbols:**

```
ffffffff8197c860-ffffffff8197c95f: __sk_msg_free_partial (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
