# Function: <code>skb_append_datato_frags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_append_datato_frags(struct sock *sk, struct sk_buff *skb, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81707f90)
Location: net/core/skbuff.c:2956
Inline: False
```
**Symbols:**

```
ffffffff81707f90-ffffffff817081a6: skb_append_datato_frags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_append_datato_frags(struct sock *sk, struct sk_buff *skb, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176e700)
Location: net/core/skbuff.c:2954
Inline: False
```
**Symbols:**

```
ffffffff8176e700-ffffffff8176e915: skb_append_datato_frags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_append_datato_frags(struct sock *sk, struct sk_buff *skb, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179bbc0)
Location: net/core/skbuff.c:2951
Inline: False
```
**Symbols:**

```
ffffffff8179bbc0-ffffffff8179bdd2: skb_append_datato_frags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_append_datato_frags(struct sock *sk, struct sk_buff *skb, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b7e00)
Location: net/core/skbuff.c:2992
Inline: False
```
**Symbols:**

```
ffffffff817b7e00-ffffffff817b7ffa: skb_append_datato_frags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_append_datato_frags(struct sock *sk, struct sk_buff *skb, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830560)
Location: net/core/skbuff.c:3374
Inline: False
```
**Symbols:**

```
ffffffff81830560-ffffffff81830763: skb_append_datato_frags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_append_datato_frags(struct sock *sk, struct sk_buff *skb, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187aa30)
Location: net/core/skbuff.c:3390
Inline: False
```
**Symbols:**

```
ffffffff8187aa30-ffffffff8187ac22: skb_append_datato_frags (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
