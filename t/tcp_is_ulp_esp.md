# Function: <code>tcp_is_ulp_esp</code>

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
bool tcp_is_ulp_esp(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b223e0)
Location: net/xfrm/espintcp.c:429
Inline: False
```
**Symbols:**

```
ffffffff81b223e0-ffffffff81b22405: tcp_is_ulp_esp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_is_ulp_esp(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b30de0)
Location: net/xfrm/espintcp.c:433
Inline: False
```
**Symbols:**

```
ffffffff81b30de0-ffffffff81b30e05: tcp_is_ulp_esp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_is_ulp_esp(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b1eb10)
Location: net/xfrm/espintcp.c:433
Inline: False
```
**Symbols:**

```
ffffffff81b1eb10-ffffffff81b1eb35: tcp_is_ulp_esp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcp_is_ulp_esp(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81be3770)
Location: net/xfrm/espintcp.c:433
Inline: False
```
**Symbols:**

```
ffffffff81be3770-ffffffff81be3795: tcp_is_ulp_esp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_is_ulp_esp(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81d7aaa0)
Location: net/xfrm/espintcp.c:431
Inline: False
```
**Symbols:**

```
ffffffff81d7aaa0-ffffffff81d7aacd: tcp_is_ulp_esp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_is_ulp_esp(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81f47a40)
Location: net/xfrm/espintcp.c:431
Inline: False
```
**Symbols:**

```
ffffffff81f47a40-ffffffff81f47a6d: tcp_is_ulp_esp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_is_ulp_esp(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81fa74f0)
Location: net/xfrm/espintcp.c:440
Inline: False
```
**Symbols:**

```
ffffffff81fa74f0-ffffffff81fa751d: tcp_is_ulp_esp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_is_ulp_esp(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff820747a0)
Location: net/xfrm/espintcp.c:440
Inline: False
```
**Symbols:**

```
ffffffff820747a0-ffffffff820747cd: tcp_is_ulp_esp (STB_GLOBAL)
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
