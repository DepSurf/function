# Function: <code>udp_reuseport_add_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f4ab1)
Location: net/ipv4/udp.c:202
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81825b7c)
Location: net/ipv4/udp.c:203
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81847b26)
Location: net/ipv4/udp.c:215
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff818c7586)
Location: net/ipv4/udp.c:215
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff8191e8a9)
Location: net/ipv4/udp.c:209
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff8194d6a9)
Location: net/ipv4/udp.c:211
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff819b1e88)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff819e8c0e)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_reuseport_add_sock(struct sock *sk, struct udp_hslot *hslot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad1af0)
Location: net/ipv4/udp.c:198
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81ad1af0-ffffffff81ad1bce: udp_reuseport_add_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_reuseport_add_sock(struct sock *sk, struct udp_hslot *hslot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81addb20)
Location: net/ipv4/udp.c:199
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81addb20-ffffffff81addbfe: udp_reuseport_add_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ace4a0)
Location: net/ipv4/udp.c:199
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8ce6b)
Location: net/ipv4/udp.c:199
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1b3b4)
Location: net/ipv4/udp.c:199
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee1d9c)
Location: net/ipv4/udp.c:206
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f417b8)
Location: net/ipv4/udp.c:208
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82007418)
Location: net/ipv4/udp.c:208
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffff800010c9c168)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (c0da8864)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (c000000000dae224)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffe0007fb176)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff81988a7e)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff8194253e)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff819f324e)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff819fbb27)
Location: net/ipv4/udp.c:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
</ul>
