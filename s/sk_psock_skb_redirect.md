# Function: <code>sk_psock_skb_redirect</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sk_psock_skb_redirect(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3c9c0)
Location: net/core/skmsg.c:686
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
**Symbols:**

```
ffffffff81a3c9c0-ffffffff81a3ca71: sk_psock_skb_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sk_psock_skb_redirect(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3f090)
Location: net/core/skmsg.c:762
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
**Symbols:**

```
ffffffff81a3f090-ffffffff81a3f101: sk_psock_skb_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_psock_skb_redirect(struct sk_psock *from, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4e120)
Location: net/core/skmsg.c:885
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
**Symbols:**

```
ffffffff81a4e120-ffffffff81a4e1fb: sk_psock_skb_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_psock_skb_redirect(struct sk_psock *from, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b06e10)
Location: net/core/skmsg.c:880
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
**Symbols:**

```
ffffffff81b06e10-ffffffff81b06eeb: sk_psock_skb_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_psock_skb_redirect(struct sk_psock *from, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8bab0)
Location: net/core/skmsg.c:900
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
**Symbols:**

```
ffffffff81c8bab0-ffffffff81c8bbbb: sk_psock_skb_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_psock_skb_redirect(struct sk_psock *from, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e478a0)
Location: net/core/skmsg.c:907
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
**Symbols:**

```
ffffffff81e478a0-ffffffff81e479ab: sk_psock_skb_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_psock_skb_redirect(struct sk_psock *from, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea2f30)
Location: net/core/skmsg.c:897
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
**Symbols:**

```
ffffffff81ea2f30-ffffffff81ea303d: sk_psock_skb_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_psock_skb_redirect(struct sk_psock *from, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f65250)
Location: net/core/skmsg.c:903
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
**Symbols:**

```
ffffffff81f65250-ffffffff81f6535d: sk_psock_skb_redirect (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_psock *from</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb</code> ➡️ <code>from, skb</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
