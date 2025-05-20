# Function: <code>tcp_model_timeout</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8199f050)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff8199f050-ffffffff8199f0a8: tcp_model_timeout.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_timer.c (ffffffff819d5af0)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff819d5af0-ffffffff819d5b48: tcp_model_timeout.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_timer.c (ffffffff81ac2130)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81ac2130-ffffffff81ac2188: tcp_model_timeout.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81acdd67)
Location: net/ipv4/tcp_timer.c:182
Inline: True
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
In net/ipv4/tcp_timer.c (ffffffff81ab8e17)
Location: net/ipv4/tcp_timer.c:182
Inline: True
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
In net/ipv4/tcp_timer.c (ffffffff81b76062)
Location: net/ipv4/tcp_timer.c:182
Inline: True
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
In net/ipv4/tcp_timer.c (ffffffff81d059d2)
Location: net/ipv4/tcp_timer.c:182
Inline: True
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
In net/ipv4/tcp_timer.c (ffffffff81ecab12)
Location: net/ipv4/tcp_timer.c:182
Inline: True
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
In net/ipv4/tcp_timer.c (ffffffff81f295bc)
Location: net/ipv4/tcp_timer.c:182
Inline: True
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
In net/ipv4/tcp_timer.c (ffffffff81fee0fd)
Location: net/ipv4/tcp_timer.c:188
Inline: True
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
In net/ipv4/tcp_timer.c (ffff800010c88498)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffff800010c88498-ffff800010c88520: tcp_model_timeout.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_timer.c (c0d97acc)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
c0d97acc-c0d97b3c: tcp_model_timeout.constprop.0 (STB_LOCAL)
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
In net/ipv4/tcp_timer.c (c000000000d95970)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
c000000000d95970-c000000000d95a08: tcp_model_timeout.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_timer.c (ffffffe0007e9a1a)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffe0007e9a1a-ffffffe0007e9aca: tcp_model_timeout.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_timer.c (ffffffff81975960)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81975960-ffffffff819759b8: tcp_model_timeout.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_timer.c (ffffffff8192f420)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff8192f420-ffffffff8192f478: tcp_model_timeout.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_timer.c (ffffffff819e0130)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff819e0130-ffffffff819e0188: tcp_model_timeout.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_timer.c (ffffffff819e9df0)
Location: net/ipv4/tcp_timer.c:164
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff819e9df0-ffffffff819e9e48: tcp_model_timeout.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
