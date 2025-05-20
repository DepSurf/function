# Function: <code>sk_msg_free_elem</code>

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
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e6a70)
Location: net/core/skmsg.c:157
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff818e6a70-ffffffff818e6b66: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81936430)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81936430-ffffffff8193652e: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81969400)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81969400-ffffffff819694fe: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3ce30)
Location: net/core/skmsg.c:167
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81a3ce30-ffffffff81a3cf37: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3e330)
Location: net/core/skmsg.c:167
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81a3e330-ffffffff81a3e42b: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4dd9f)
Location: net/core/skmsg.c:167
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_trim
Direct callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81a4c640-ffffffff81a4c73b: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b066ab)
Location: net/core/skmsg.c:167
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_trim
Direct callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81b04b40-ffffffff81b04c75: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8a9a0)
Location: net/core/skmsg.c:176
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81c8a9a0-ffffffff81c8ab36: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e455d0)
Location: net/core/skmsg.c:176
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81e455d0-ffffffff81e45771: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea0bf0)
Location: net/core/skmsg.c:177
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81ea0bf0-ffffffff81ea0d8f: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f632a0)
Location: net/core/skmsg.c:177
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81f632a0-ffffffff81f63438: sk_msg_free_elem (STB_LOCAL)
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
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffff800010c0e6c0)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffff800010c0e6c0-ffff800010c0e7b4: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c0d273b8)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
c0d273b8-c0d274ac: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c000000000cfb3f0)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
c000000000cfb3f0-c000000000cfb578: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffe00078ba2e)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffe00078ba2e-ffffffe00078baf0: sk_msg_free_elem (STB_LOCAL)
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
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff819093d0)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff819093d0-ffffffff819094ce: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c31e0)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff818c31e0-ffffffff818c32de: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8195a400)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff8195a400-ffffffff8195a4fe: sk_msg_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sk_msg_free_elem(struct sock *sk, struct sk_msg *msg, u32 i, bool charge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8197c620)
Location: net/core/skmsg.c:166
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff8197c620-ffffffff8197c71e: sk_msg_free_elem (STB_LOCAL)
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
