# Function: <code>sock_pfree</code>

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
void sock_pfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4d30)
Location: net/core/sock.c:2169
Inline: False
```
**Symbols:**

```
ffffffff819e4d30-ffffffff819e4d62: sock_pfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sock_pfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4480)
Location: net/core/sock.c:2161
Inline: False
```
**Symbols:**

```
ffffffff819e4480-ffffffff819e44b2: sock_pfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sock_pfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ca690)
Location: net/core/sock.c:2184
Inline: False
```
**Symbols:**

```
ffffffff819ca690-ffffffff819ca6c2: sock_pfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sock_pfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2308
Inline: False
```
**Symbols:**

```
ffffffff81d34ab3-ffffffff81d34ad3: sock_pfree.cold (STB_LOCAL)
ffffffff81a79e70-ffffffff81a79ecb: sock_pfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_pfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81bedbb0)
Location: net/core/sock.c:2475
Inline: True
```
**Symbols:**

```
ffffffff81f01045-ffffffff81f01065: sock_pfree.cold (STB_LOCAL)
ffffffff81bedb70-ffffffff81bedbd0: sock_pfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_pfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81d9ae24)
Location: net/core/sock.c:2554
Inline: True
```
**Symbols:**

```
ffffffff820aab76-ffffffff820aab96: sock_pfree.cold (STB_LOCAL)
ffffffff81d9adf0-ffffffff81d9ae67: sock_pfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_pfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81e0969c)
Location: net/core/sock.c:2603
Inline: True
```
**Symbols:**

```
ffffffff8212c09b-ffffffff8212c0b8: sock_pfree.cold (STB_LOCAL)
ffffffff81e09670-ffffffff81e096d4: sock_pfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_pfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81ec608c)
Location: net/core/sock.c:2583
Inline: True
```
**Symbols:**

```
ffffffff8220dd2a-ffffffff8220dd47: sock_pfree.cold (STB_LOCAL)
ffffffff81ec6060-ffffffff81ec60c4: sock_pfree (STB_GLOBAL)
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
