# Function: <code>cpu_rmap_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cpu_rmap_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff81415d90)
Location: lib/cpu_rmap.c:69
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff81415d90-ffffffff81415d9b: cpu_rmap_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_rmap_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8145df74)
Location: lib/cpu_rmap.c:69
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
**Symbols:**

```
ffffffff8145dbd0-ffffffff8145dbdb: cpu_rmap_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cpu_rmap_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8147c9a4)
Location: lib/cpu_rmap.c:69
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
**Symbols:**

```
ffffffff8147c690-ffffffff8147c69b: cpu_rmap_release (STB_LOCAL)
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
In lib/cpu_rmap.c (ffffffff814859cc)
Location: lib/cpu_rmap.c:69
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_put
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
In lib/cpu_rmap.c (ffffffff814c1df7)
Location: lib/cpu_rmap.c:69
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff814f2d40)
Location: lib/cpu_rmap.c:69
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff81507070)
Location: lib/cpu_rmap.c:69
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff8153527e)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff8155608e)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff815df703)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff815fcea3)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff815dfc13)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff8164b723)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff817621d3)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff81890ef3)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff818d39e3)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff81925af2)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffff80001066265c)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_put
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
In lib/cpu_rmap.c (c080b304)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_put
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
In lib/cpu_rmap.c (c00000000081686c)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_put
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
In lib/cpu_rmap.c (ffffffe00048f0aa)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff8154e66e)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff8153e94e)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff8154a3ae)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
In lib/cpu_rmap.c (ffffffff815641fe)
Location: lib/cpu_rmap.c:66
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
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
</ul>
