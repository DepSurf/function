# Function: <code>sk_psock_stop_verdict</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sk_psock_stop_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a40551)
Location: net/core/skmsg.c:1056
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
Direct callers:
  - net/core/sock_map.c:sock_map_del_link
```
**Symbols:**

```
ffffffff81a40680-ffffffff81a406b4: sk_psock_stop_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sk_psock_stop_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4efd2)
Location: net/core/skmsg.c:1205
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
Direct callers:
  - net/core/sock_map.c:sock_map_unref
```
**Symbols:**

```
ffffffff81a4f100-ffffffff81a4f129: sk_psock_stop_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sk_psock_stop_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b07b52)
Location: net/core/skmsg.c:1215
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
Direct callers:
  - net/core/sock_map.c:sock_map_unref
```
**Symbols:**

```
ffffffff81b07cb0-ffffffff81b07d06: sk_psock_stop_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sk_psock_stop_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8d90e)
Location: net/core/skmsg.c:1235
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
Direct callers:
  - net/core/sock_map.c:sock_map_unref
```
**Symbols:**

```
ffffffff81c8daa0-ffffffff81c8db00: sk_psock_stop_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sk_psock_stop_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e4878c)
Location: net/core/skmsg.c:1228
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
Direct callers:
  - net/core/sock_map.c:sock_map_unref
```
**Symbols:**

```
ffffffff81e48960-ffffffff81e489c0: sk_psock_stop_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sk_psock_stop_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea3e1c)
Location: net/core/skmsg.c:1239
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
Direct callers:
  - net/core/sock_map.c:sock_map_unref
```
**Symbols:**

```
ffffffff81ea4000-ffffffff81ea4060: sk_psock_stop_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sk_psock_stop_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f6671c)
Location: net/core/skmsg.c:1248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
Direct callers:
  - net/core/sock_map.c:sock_map_unref
```
**Symbols:**

```
ffffffff81f66900-ffffffff81f66960: sk_psock_stop_verdict (STB_GLOBAL)
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
