# Function: <code>inet_csk_find_open_port</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81820fd2)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189fd92)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f457a)
Location: net/ipv4/inet_connection_sock.c:168
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81922309)
Location: net/ipv4/inet_connection_sock.c:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81984a8f)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819bb4ff)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inet_bind_hashbucket *inet_csk_find_open_port(struct sock *sk, struct inet_bind_bucket **tb_ret, int *port_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5e00)
Location: net/ipv4/inet_connection_sock.c:182
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81aa5e00-ffffffff81aa609b: inet_csk_find_open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inet_bind_hashbucket *inet_csk_find_open_port(struct sock *sk, struct inet_bind_bucket **tb_ret, int *port_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0440)
Location: net/ipv4/inet_connection_sock.c:182
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ab0440-ffffffff81ab06e1: inet_csk_find_open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inet_bind_hashbucket *inet_csk_find_open_port(struct sock *sk, struct inet_bind_bucket **tb_ret, int *port_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b620)
Location: net/ipv4/inet_connection_sock.c:182
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81a9b620-ffffffff81a9b8ca: inet_csk_find_open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inet_bind_hashbucket *inet_csk_find_open_port(struct sock *sk, struct inet_bind_bucket **tb_ret, int *port_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b56c50)
Location: net/ipv4/inet_connection_sock.c:190
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81b56c50-ffffffff81b56efa: inet_csk_find_open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4af0)
Location: net/ipv4/inet_connection_sock.c:194
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ce4af0-ffffffff81ce4dde: inet_csk_find_open_port.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7db0)
Location: net/ipv4/inet_connection_sock.c:302
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ea7db0-ffffffff81ea831c: inet_csk_find_open_port.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f065f0)
Location: net/ipv4/inet_connection_sock.c:323
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81f065f0-ffffffff81f06b94: inet_csk_find_open_port.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fca8e0)
Location: net/ipv4/inet_connection_sock.c:321
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81fca8e0-ffffffff81fcaeba: inet_csk_find_open_port.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6e16c)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7cd44)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d73cfc)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d287e)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195b36f)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81914e5f)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c5b3f)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819cf623)
Location: net/ipv4/inet_connection_sock.c:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
</details>
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
</ul>
