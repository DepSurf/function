# Function: <code>__register_prot_hook</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __register_prot_hook(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819aebc0)
Location: net/packet/af_packet.c:304
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff819aebc0-ffffffff819aec12: __register_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __register_prot_hook(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e55c0)
Location: net/packet/af_packet.c:305
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff819e55c0-ffffffff819e5612: __register_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a58a21)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81a54fc0-ffffffff81a55007: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a8eb18)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81a8bbb0-ffffffff81a8bbf7: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b89bec)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81b88f70-ffffffff81b89028: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b99707)
Location: net/packet/af_packet.c:301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81b98a70-ffffffff81b98b25: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b88bd0)
Location: net/packet/af_packet.c:301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81b87990-ffffffff81b87a20: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c54cd1)
Location: net/packet/af_packet.c:302
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81c53eb0-ffffffff81c53f40: __register_prot_hook.part.0 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81df4edb)
Location: net/packet/af_packet.c:338
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81df2a10-ffffffff81df2ad0: __register_prot_hook.part.0 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81fc7863)
Location: net/packet/af_packet.c:338
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81fc6df0-ffffffff81fc6eb0: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __register_prot_hook(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82027af0)
Location: net/packet/af_packet.c:336
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff82027af0-ffffffff82027bca: __register_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __register_prot_hook(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f7350)
Location: net/packet/af_packet.c:336
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff820f7350-ffffffff820f742a: __register_prot_hook (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffff800010d5bc98)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffff800010d584a0-ffff800010d5850c: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (c0e5bde8)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
c0e579e0-c0e57a2c: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (c000000000e97640)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
c000000000e90a40-c000000000e90aec: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffe000891ff6)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffe000890486-ffffffe0008904d4: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a2e1a8)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81a2b240-ffffffff81a2b287: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff819eb398)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff819e8430-ffffffff819e8477: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a99d58)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81a96df0-ffffffff81a96e37: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa6a87)
Location: net/packet/af_packet.c:297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81aa1920-ffffffff81aa1967: __register_prot_hook.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
