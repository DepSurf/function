# Function: <code>unix_state_double_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81393f7d)
Location: security/apparmor/af_unix.c:566
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff817bd9f0)
Location: net/unix/af_unix.c:1084
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff817bd9f0-ffffffff817bda56: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813cf770)
Location: security/apparmor/af_unix.c:566
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8182a960)
Location: net/unix/af_unix.c:1072
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8182a960-ffffffff8182a9c6: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813e6e50)
Location: security/apparmor/af_unix.c:566
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8185c3e0)
Location: net/unix/af_unix.c:1077
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8185c3e0-ffffffff8185c446: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813f3c37)
Location: security/apparmor/af_unix.c:574
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81881660)
Location: net/unix/af_unix.c:1079
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81881660-ffffffff818816b3: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8141be1d)
Location: security/apparmor/af_unix.c:574
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81902800)
Location: net/unix/af_unix.c:1080
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81902800-ffffffff81902853: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8144e0f0)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81958720)
Location: net/unix/af_unix.c:1070
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81958720-ffffffff81958770: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8146b0c0)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8198d320)
Location: net/unix/af_unix.c:1077
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8198d320-ffffffff8198d370: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814980bb)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff819f8ca0)
Location: net/unix/af_unix.c:1074
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff819f8ca0-ffffffff819f8cf3: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b1feb)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81a2f8f0)
Location: net/unix/af_unix.c:1086
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81a2f8f0-ffffffff81a2f943: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff815113cb)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81b27bd9)
Location: net/unix/af_unix.c:1109
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81b235c0-ffffffff81b23613: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8152e21b)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81b364b9)
Location: net/unix/af_unix.c:1100
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81b31fb0-ffffffff81b32003: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81534546)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81b24099)
Location: net/unix/af_unix.c:1102
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81b1fcd0-ffffffff81b1fd23: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81592ac6)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81be8729)
Location: net/unix/af_unix.c:1188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81be4990-ffffffff81be49e3: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816348ba)
Location: security/apparmor/af_unix.c:600
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81d80e1e)
Location: net/unix/af_unix.c:1268
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81d7cad0-ffffffff81d7cb30: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816e97ee)
Location: security/apparmor/af_unix.c:620
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81f4e9d6)
Location: net/unix/af_unix.c:1321
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81f49be0-ffffffff81f49c40: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81722fde)
Location: security/apparmor/af_unix.c:620
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81fae28d)
Location: net/unix/af_unix.c:1342
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81fa9860-ffffffff81fa98c9: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81761a7f)
Location: security/apparmor/af_unix.c:620
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8207ab6b)
Location: net/unix/af_unix.c:1328
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff82076150-ffffffff8207619f: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a9810)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffff800010cf09a8)
Location: net/unix/af_unix.c:1086
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffff800010cf09a8-ffff800010cf0b54: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c075964c)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (c0df6de0)
Location: net/unix/af_unix.c:1086
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
c0df6de0-c0df6e38: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c000000000726e40)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (c000000000e13740)
Location: net/unix/af_unix.c:1086
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
c000000000e13740-c000000000e13800: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f296a)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffe00083bb82)
Location: net/unix/af_unix.c:1086
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffe00083bb82-ffffffe00083bbfa: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814aa5cb)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff819cef80)
Location: net/unix/af_unix.c:1086
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff819cef80-ffffffff819cefd3: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8149afeb)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8198bd40)
Location: net/unix/af_unix.c:1086
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8198bd40-ffffffff8198bd93: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a666b)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81a39a00)
Location: net/unix/af_unix.c:1086
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81a39a00-ffffffff81a39a53: unix_state_double_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_lock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814bef4f)
Location: security/apparmor/af_unix.c:575
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81a45810)
Location: net/unix/af_unix.c:1086
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81a45810-ffffffff81a45863: unix_state_double_lock (STB_LOCAL)
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
