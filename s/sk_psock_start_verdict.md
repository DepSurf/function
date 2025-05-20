# Function: <code>sk_psock_start_verdict</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void sk_psock_start_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a405b0)
Location: net/core/skmsg.c:1017
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff81a405b0-ffffffff81a405ef: sk_psock_start_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sk_psock_start_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4f0c0)
Location: net/core/skmsg.c:1195
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff81a4f0c0-ffffffff81a4f0fb: sk_psock_start_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sk_psock_start_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b07c70)
Location: net/core/skmsg.c:1205
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff81b07c70-ffffffff81b07cab: sk_psock_start_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_psock_start_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8da50)
Location: net/core/skmsg.c:1225
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff81c8da50-ffffffff81c8da9f: sk_psock_start_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_psock_start_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e48900)
Location: net/core/skmsg.c:1218
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff81e48900-ffffffff81e4894f: sk_psock_start_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_psock_start_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea3fa0)
Location: net/core/skmsg.c:1229
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff81ea3fa0-ffffffff81ea3fef: sk_psock_start_verdict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_psock_start_verdict(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f668a0)
Location: net/core/skmsg.c:1238
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
ffffffff81f668a0-ffffffff81f668ef: sk_psock_start_verdict (STB_GLOBAL)
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
