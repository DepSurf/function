# Function: <code>unix_state_double_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81394047)
Location: security/apparmor/af_unix.c:581
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff817be4e0)
Location: net/unix/af_unix.c:1099
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff817be4e0-ffffffff817be521: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813cf82c)
Location: security/apparmor/af_unix.c:581
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8182b480)
Location: net/unix/af_unix.c:1087
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8182b480-ffffffff8182b4c1: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813e6f0c)
Location: security/apparmor/af_unix.c:581
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8185cea0)
Location: net/unix/af_unix.c:1092
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8185cea0-ffffffff8185cee1: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813f3d15)
Location: security/apparmor/af_unix.c:589
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff818816c0)
Location: net/unix/af_unix.c:1094
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff818816c0-ffffffff81881700: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8141befb)
Location: security/apparmor/af_unix.c:589
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81902860)
Location: net/unix/af_unix.c:1095
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81902860-ffffffff819028a0: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8144e1af)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81959720)
Location: net/unix/af_unix.c:1085
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81959720-ffffffff81959760: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8146b192)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8198e440)
Location: net/unix/af_unix.c:1092
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8198e440-ffffffff8198e480: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81498191)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff819f99f0)
Location: net/unix/af_unix.c:1089
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff819f99f0-ffffffff819f9a24: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b20c1)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81a30670)
Location: net/unix/af_unix.c:1101
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81a30670-ffffffff81a306a4: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8151149e)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81b27c5a)
Location: net/unix/af_unix.c:1124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8152e2ee)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81b36539)
Location: net/unix/af_unix.c:1115
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8153460d)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81b24119)
Location: net/unix/af_unix.c:1117
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81592b8d)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81be87b3)
Location: net/unix/af_unix.c:1203
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8163497b)
Location: security/apparmor/af_unix.c:615
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81d8103c)
Location: net/unix/af_unix.c:1283
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816e98c2)
Location: security/apparmor/af_unix.c:635
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81f4eb1d)
Location: net/unix/af_unix.c:1336
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff817230b1)
Location: security/apparmor/af_unix.c:635
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81fae3f6)
Location: net/unix/af_unix.c:1357
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81761b52)
Location: security/apparmor/af_unix.c:635
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8207ad73)
Location: net/unix/af_unix.c:1341
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a98f0)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffff800010cf1a94)
Location: net/unix/af_unix.c:1101
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c0759728)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (c0df7d2c)
Location: net/unix/af_unix.c:1101
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
c0df7d2c-c0df7da8: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c000000000726f08)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (c000000000e14d30)
Location: net/unix/af_unix.c:1101
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
c000000000e14d30-c000000000e14e00: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f29fc)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffe00083ccc4)
Location: net/unix/af_unix.c:1101
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffe00083ccc4-ffffffe00083cdaa: unix_state_double_unlock (STB_LOCAL)
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
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814aa6a1)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff819cfd00)
Location: net/unix/af_unix.c:1101
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff819cfd00-ffffffff819cfd34: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8149b0c1)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff8198cac0)
Location: net/unix/af_unix.c:1101
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8198cac0-ffffffff8198caf4: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a6741)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81a3a780)
Location: net/unix/af_unix.c:1101
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81a3a780-ffffffff81a3a7b4: unix_state_double_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void unix_state_double_unlock(struct sock *sk1, struct sock *sk2);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814bf023)
Location: security/apparmor/af_unix.c:590
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In net/unix/af_unix.c (ffffffff81a45870)
Location: net/unix/af_unix.c:1101
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81a45870-ffffffff81a458b0: unix_state_double_unlock (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
