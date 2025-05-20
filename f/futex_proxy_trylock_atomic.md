# Function: <code>futex_proxy_trylock_atomic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81101e8d)
Location: kernel/futex.c:1536
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811093d5)
Location: kernel/futex.c:1626
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff81110bc5)
Location: kernel/futex.c:1635
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff81112162)
Location: kernel/futex.c:1725
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff8111cb92)
Location: kernel/futex.c:1803
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff81129547)
Location: kernel/futex.c:1785
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff81135637)
Location: kernel/futex.c:1853
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff81140f25)
Location: kernel/futex.c:1867
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff8114c9e6)
Location: kernel/futex.c:1949
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff8115d320)
Location: kernel/futex.c:1875
Inline: True
Direct callers:
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff8115d320-ffffffff8115d475: futex_proxy_trylock_atomic.constprop.0 (STB_LOCAL)
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
In kernel/futex.c (ffffffff81158eb0)
Location: kernel/futex.c:1853
Inline: True
Direct callers:
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81158eb0-ffffffff81158fdf: futex_proxy_trylock_atomic.constprop.0 (STB_LOCAL)
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
In kernel/futex.c (ffffffff8115a7d7)
Location: kernel/futex.c:1856
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff8117f64c)
Location: kernel/futex.c:2030
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex/requeue.c (ffffffff811b5afa)
Location: kernel/futex/requeue.c:267
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
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
In kernel/futex/requeue.c (ffffffff811f6c2a)
Location: kernel/futex/requeue.c:267
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
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
In kernel/futex/requeue.c (ffffffff8120b417)
Location: kernel/futex/requeue.c:267
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
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
In kernel/futex/requeue.c (ffffffff812229bd)
Location: kernel/futex/requeue.c:269
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
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
In kernel/futex.c (ffff8000101babb4)
Location: kernel/futex.c:1949
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (c04033bc)
Location: kernel/futex.c:1949
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (c000000000220e04)
Location: kernel/futex.c:1949
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffe00013ed78)
Location: kernel/futex.c:1949
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff81145006)
Location: kernel/futex.c:1949
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff81138316)
Location: kernel/futex.c:1949
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff81142eb6)
Location: kernel/futex.c:1949
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
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
In kernel/futex.c (ffffffff81150496)
Location: kernel/futex.c:1949
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
```
</details>
</li>
</ul>

## Differences
