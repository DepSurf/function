# Function: <code>cookie_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff817aada0)
Location: net/ipv4/syncookies.c:56
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff817feee0)
Location: net/ipv6/syncookies.c:47
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
```
**Symbols:**

```
ffffffff817aada0-ffffffff817aaf03: cookie_hash (STB_LOCAL)
ffffffff817feee0-ffffffff817ff043: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff818188a0)
Location: net/ipv4/syncookies.c:53
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff8186e870)
Location: net/ipv6/syncookies.c:46
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff818188a0-ffffffff81818a07: cookie_hash (STB_LOCAL)
ffffffff8186e870-ffffffff8186e9d7: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff8184a100)
Location: net/ipv4/syncookies.c:53
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff818a17c0)
Location: net/ipv6/syncookies.c:46
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff8184a100-ffffffff8184a267: cookie_hash (STB_LOCAL)
ffffffff818a17c0-ffffffff818a1927: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff8186db40)
Location: net/ipv4/syncookies.c:52
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff818c7e10)
Location: net/ipv6/syncookies.c:45
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff8186db40-ffffffff8186dc19: cookie_hash (STB_LOCAL)
ffffffff818c7e10-ffffffff818c7ef0: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff818ee480)
Location: net/ipv4/syncookies.c:52
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff8194b3b0)
Location: net/ipv6/syncookies.c:45
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff818ee480-ffffffff818ee564: cookie_hash (STB_LOCAL)
ffffffff8194b3b0-ffffffff8194b497: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81944e10)
Location: net/ipv4/syncookies.c:52
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819a4660)
Location: net/ipv6/syncookies.c:45
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81944e10-ffffffff81944ee7: cookie_hash (STB_LOCAL)
ffffffff819a4660-ffffffff819a4736: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81975100)
Location: net/ipv4/syncookies.c:52
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819db170)
Location: net/ipv6/syncookies.c:45
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81975100-ffffffff819751d7: cookie_hash (STB_LOCAL)
ffffffff819db170-ffffffff819db246: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff819decb0)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a49df0)
Location: net/ipv6/syncookies.c:40
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff819decb0-ffffffff819ded8c: cookie_hash (STB_LOCAL)
ffffffff81a49df0-ffffffff81a49ec6: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81a15d50)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a809b0)
Location: net/ipv6/syncookies.c:40
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81a15d50-ffffffff81a15e2c: cookie_hash (STB_LOCAL)
ffffffff81a809b0-ffffffff81a80a86: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b06dc0)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b7b640)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81b06dc0-ffffffff81b06e9c: cookie_hash (STB_LOCAL)
ffffffff81b7b640-ffffffff81b7b700: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b14fb0)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b8a680)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81b14fb0-ffffffff81b1508c: cookie_hash (STB_LOCAL)
ffffffff81b8a680-ffffffff81b8a740: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b02db0)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b794d0)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81b02db0-ffffffff81b02e8e: cookie_hash (STB_LOCAL)
ffffffff81b794d0-ffffffff81b7959a: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81bc4fc0)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81c44130)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81bc4fc0-ffffffff81bc50cf: cookie_hash (STB_LOCAL)
ffffffff81c44130-ffffffff81c44219: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81d5a110)
Location: net/ipv4/syncookies.c:46
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81de3080)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81d5a110-ffffffff81d5a23d: cookie_hash (STB_LOCAL)
ffffffff81de3080-ffffffff81de318b: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81f24500)
Location: net/ipv4/syncookies.c:46
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81fb56c0)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81f24500-ffffffff81f24629: cookie_hash (STB_LOCAL)
ffffffff81fb56c0-ffffffff81fb57cb: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81f84090)
Location: net/ipv4/syncookies.c:46
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff82015de0)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81f84090-ffffffff81f841b9: cookie_hash (STB_LOCAL)
ffffffff82015de0-ffffffff82015eeb: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff8204a740)
Location: net/ipv4/syncookies.c:45
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff820e4f30)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff8204a740-ffffffff8204a869: cookie_hash (STB_LOCAL)
ffffffff820e4f30-ffffffff820e503b: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (ffff800010cd1960)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffff800010d4c1c8)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffff800010cd1960-ffff800010cd1a58: cookie_hash (STB_LOCAL)
ffff800010d4c1c8-ffff800010d4c2cc: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (c0ddb7e0)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (c0e4d410)
Location: net/ipv6/syncookies.c:40
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
c0ddb7e0-c0ddb8bc: cookie_hash (STB_LOCAL)
c0e4d410-c0e4d504: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/syncookies.c (c000000000defb90)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (c000000000e827c0)
Location: net/ipv6/syncookies.c:40
Inline: True
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
c000000000defb90-c000000000defcec: cookie_hash (STB_LOCAL)
c000000000e827c0-c000000000e828ec: cookie_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffe000822dfc)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffe000884f6a)
Location: net/ipv6/syncookies.c:40
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffe000822dfc-ffffffe000822ebe: cookie_hash (STB_LOCAL)
ffffffe000884f6a-ffffffe00088505e: cookie_hash (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff819b53e0)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a20040)
Location: net/ipv6/syncookies.c:40
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff819b53e0-ffffffff819b54bc: cookie_hash (STB_LOCAL)
ffffffff81a20040-ffffffff81a20116: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff819721d0)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819dce00)
Location: net/ipv6/syncookies.c:40
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff819721d0-ffffffff819722ac: cookie_hash (STB_LOCAL)
ffffffff819dce00-ffffffff819dced6: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81a1fc80)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a8aac0)
Location: net/ipv6/syncookies.c:40
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81a1fc80-ffffffff81a1fd5c: cookie_hash (STB_LOCAL)
ffffffff81a8aac0-ffffffff81a8ab96: cookie_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81a2b180)
Location: net/ipv4/syncookies.c:48
Inline: False
Direct callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a97720)
Location: net/ipv6/syncookies.c:40
Inline: False
Direct callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
ffffffff81a2b180-ffffffff81a2b25c: cookie_hash (STB_LOCAL)
ffffffff81a97720-ffffffff81a977f6: cookie_hash (STB_LOCAL)
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
