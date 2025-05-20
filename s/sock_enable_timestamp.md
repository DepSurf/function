# Function: <code>sock_enable_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817041f0)
Location: net/core/sock.c:2536
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestampns
```
**Symbols:**

```
ffffffff817041f0-ffffffff81704229: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8176ad00)
Location: net/core/sock.c:2604
Inline: False
Direct callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff8176ad00-ffffffff8176ad35: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81797dc0)
Location: net/core/sock.c:2631
Inline: False
Direct callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff81797dc0-ffffffff81797df5: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b5970)
Location: net/core/sock.c:2798
Inline: False
Direct callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff817b5970-ffffffff817b59a2: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182dec0)
Location: net/core/sock.c:2859
Inline: False
Direct callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff8182dec0-ffffffff8182def2: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818782b0)
Location: net/core/sock.c:2934
Inline: False
Direct callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff818782b0-ffffffff818782e2: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81898a40)
Location: net/core/sock.c:2885
Inline: False
Direct callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81898a40-ffffffff81898a72: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e2fe0)
Location: net/core/sock.c:3033
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818e2fe0-ffffffff818e3011: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819151c0)
Location: net/core/sock.c:3048
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819151c0-ffffffff819151f1: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sock_enable_timestamp(struct sock *sk, enum sock_flags flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6214)
Location: net/core/sock.c:3177
Inline: True
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_enable_timestamps
```
**Symbols:**

```
ffffffff819e8670-ffffffff819e86a1: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sock_enable_timestamp(struct sock *sk, enum sock_flags flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e59e0)
Location: net/core/sock.c:3157
Inline: True
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_enable_timestamps
```
**Symbols:**

```
ffffffff819e8300-ffffffff819e8331: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sock_enable_timestamp(struct sock *sk, enum sock_flags flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cbaf1)
Location: net/core/sock.c:3180
Inline: True
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_enable_timestamps
```
**Symbols:**

```
ffffffff819ce430-ffffffff819ce465: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, enum sock_flags flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7dc80)
Location: net/core/sock.c:3306
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
```
**Symbols:**

```
ffffffff81a7dc80-ffffffff81a7dcb5: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sock_enable_timestamp(struct sock *sk, enum sock_flags flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bee042)
Location: net/core/sock.c:3492
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
```
**Symbols:**

```
ffffffff81bf2580-ffffffff81bf25cd: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_enable_timestamp(struct sock *sk, enum sock_flags flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81d9ac22)
Location: net/core/sock.c:3581
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_set_timestamping
```
**Symbols:**

```
ffffffff81d9a330-ffffffff81d9a373: sock_enable_timestamp.part.0 (STB_LOCAL)
ffffffff81d9e720-ffffffff81d9e74e: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_enable_timestamp(struct sock *sk, enum sock_flags flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81e093a2)
Location: net/core/sock.c:3614
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_set_timestamping
```
**Symbols:**

```
ffffffff81e08b90-ffffffff81e08bd3: sock_enable_timestamp.part.0 (STB_LOCAL)
ffffffff81e0cf30-ffffffff81e0cf5e: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_enable_timestamp(struct sock *sk, enum sock_flags flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81ec5d92)
Location: net/core/sock.c:3622
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_set_timestamping
```
**Symbols:**

```
ffffffff81ec5600-ffffffff81ec5643: sock_enable_timestamp.part.0 (STB_LOCAL)
ffffffff81ec98c0-ffffffff81ec98ee: sock_enable_timestamp (STB_GLOBAL)
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
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bae0f0)
Location: net/core/sock.c:3048
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffff800010bae0f0-ffff800010bae184: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccbad4)
Location: net/core/sock.c:3048
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c0ccbad4-c0ccbb54: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c83ab0)
Location: net/core/sock.c:3048
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c000000000c83ab0-c000000000c83b44: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00074003c)
Location: net/core/sock.c:3048
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffe00074003c-ffffffe0007400b6: sock_enable_timestamp (STB_GLOBAL)
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
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b51c0)
Location: net/core/sock.c:3048
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818b51c0-ffffffff818b51f1: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186f110)
Location: net/core/sock.c:3048
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff8186f110-ffffffff8186f141: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819061c0)
Location: net/core/sock.c:3048
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819061c0-ffffffff819061f1: sock_enable_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_enable_timestamp(struct sock *sk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819271f0)
Location: net/core/sock.c:3048
Inline: False
Direct callers:
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819271f0-ffffffff81927221: sock_enable_timestamp (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flag</code> ➡️ <code>enum sock_flags flag</code>
</li>
</ul>
</details>
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
