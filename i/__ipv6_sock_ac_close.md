# Function: <code>__ipv6_sock_ac_close</code>

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
void __ipv6_sock_ac_close(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81b2be80)
Location: net/ipv6/anycast.c:186
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
```
**Symbols:**

```
ffffffff81b2be80-ffffffff81b2bf6c: __ipv6_sock_ac_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ipv6_sock_ac_close(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81b3a8a0)
Location: net/ipv6/anycast.c:186
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
```
**Symbols:**

```
ffffffff81b3a8a0-ffffffff81b3a98c: __ipv6_sock_ac_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ipv6_sock_ac_close(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81b28580)
Location: net/ipv6/anycast.c:186
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
```
**Symbols:**

```
ffffffff81b28580-ffffffff81b2866c: __ipv6_sock_ac_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ipv6_sock_ac_close(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/anycast.c (0)
Location: net/ipv6/anycast.c:186
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
```
**Symbols:**

```
ffffffff81d3f26b-ffffffff81d3f29f: __ipv6_sock_ac_close.cold (STB_LOCAL)
ffffffff81bee510-ffffffff81bee615: __ipv6_sock_ac_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ipv6_sock_ac_close(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/anycast.c (0)
Location: net/ipv6/anycast.c:186
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
```
**Symbols:**

```
ffffffff81f0bbac-ffffffff81f0bbe0: __ipv6_sock_ac_close.cold (STB_LOCAL)
ffffffff81d86a70-ffffffff81d86b87: __ipv6_sock_ac_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __ipv6_sock_ac_close(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/anycast.c (0)
Location: net/ipv6/anycast.c:186
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff820b33ac-ffffffff820b33e0: __ipv6_sock_ac_close.cold (STB_LOCAL)
ffffffff81f54600-ffffffff81f54717: __ipv6_sock_ac_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __ipv6_sock_ac_close(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/anycast.c (0)
Location: net/ipv6/anycast.c:186
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff82134553-ffffffff82134580: __ipv6_sock_ac_close.cold (STB_LOCAL)
ffffffff81fb4020-ffffffff81fb4140: __ipv6_sock_ac_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __ipv6_sock_ac_close(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/anycast.c (0)
Location: net/ipv6/anycast.c:186
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff8221611c-ffffffff82216149: __ipv6_sock_ac_close.cold (STB_LOCAL)
ffffffff820818d0-ffffffff820819f0: __ipv6_sock_ac_close (STB_GLOBAL)
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
