# Function: <code>tcp_tsq_write</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190b73f)
Location: net/ipv4/tcp_output.c:788
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff8190b640-ffffffff8190b6e8: tcp_tsq_write.part.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81939a0f)
Location: net/ipv4/tcp_output.c:786
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81939900-ffffffff819399b1: tcp_tsq_write.part.51 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff8199dce2)
Location: net/ipv4/tcp_output.c:786
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff8199dbf0-ffffffff8199dc96: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff819d47a2)
Location: net/ipv4/tcp_output.c:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff819d46b0-ffffffff819d4756: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff81ac119f)
Location: net/ipv4/tcp_output.c:853
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81ac0fe0-ffffffff81ac1086: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff81accc0f)
Location: net/ipv4/tcp_output.c:1009
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81acca50-ffffffff81accaf6: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff81ab7dcf)
Location: net/ipv4/tcp_output.c:1009
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81ab7c10-ffffffff81ab7cb6: tcp_tsq_write.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_tsq_write(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b74df8)
Location: net/ipv4/tcp_output.c:1009
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81b74dd0-ffffffff81b74ea0: tcp_tsq_write (STB_LOCAL)
ffffffff81d3b3aa-ffffffff81d3b3c3: tcp_tsq_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_tsq_write(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d045a9)
Location: net/ipv4/tcp_output.c:1008
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81d04580-ffffffff81d04651: tcp_tsq_write (STB_LOCAL)
ffffffff81f07c91-ffffffff81f07cab: tcp_tsq_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_tsq_write(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec9529)
Location: net/ipv4/tcp_output.c:1008
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81ec9500-ffffffff81ec95d1: tcp_tsq_write (STB_LOCAL)
ffffffff820af6f9-ffffffff820af713: tcp_tsq_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_tsq_write(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f28091)
Location: net/ipv4/tcp_output.c:1010
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81f28060-ffffffff81f2812d: tcp_tsq_write (STB_LOCAL)
ffffffff82130ac2-ffffffff82130adb: tcp_tsq_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_tsq_write(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fecb01)
Location: net/ipv4/tcp_output.c:1062
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81fecad0-ffffffff81fecb9d: tcp_tsq_write (STB_LOCAL)
ffffffff82212296-ffffffff822122af: tcp_tsq_write.cold (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffff800010c872f0)
Location: net/ipv4/tcp_output.c:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffff800010c871c8-ffff800010c8727c: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (c0d96724)
Location: net/ipv4/tcp_output.c:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
c0d9662c-c0d966c4: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (c000000000d93d10)
Location: net/ipv4/tcp_output.c:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
c000000000d93ba0-c000000000d93c78: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffe0007e8794)
Location: net/ipv4/tcp_output.c:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffe0007e86ac-ffffffe0007e8740: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff81974612)
Location: net/ipv4/tcp_output.c:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff81974520-ffffffff819745c6: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff8192e0e2)
Location: net/ipv4/tcp_output.c:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff8192dff0-ffffffff8192e096: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff819dede2)
Location: net/ipv4/tcp_output.c:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff819decf0-ffffffff819ded96: tcp_tsq_write.part.0 (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff819e8a82)
Location: net/ipv4/tcp_output.c:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
Direct callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
**Symbols:**

```
ffffffff819e8990-ffffffff819e8a36: tcp_tsq_write.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
