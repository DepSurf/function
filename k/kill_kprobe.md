# Function: <code>kill_kprobe</code>

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
In kernel/kprobes.c (ffffffff8112de6b)
Location: kernel/kprobes.c:1968
Inline: True
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
In kernel/kprobes.c (ffffffff811360b4)
Location: kernel/kprobes.c:1968
Inline: True
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
In kernel/kprobes.c (ffffffff8113fe34)
Location: kernel/kprobes.c:1968
Inline: True
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
In kernel/kprobes.c (ffffffff81141220)
Location: kernel/kprobes.c:2050
Inline: True
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
In kernel/kprobes.c (ffffffff8114e0c0)
Location: kernel/kprobes.c:2054
Inline: True
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
In kernel/kprobes.c (ffffffff8115d0d0)
Location: kernel/kprobes.c:2098
Inline: True
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
In kernel/kprobes.c (ffffffff81169ad0)
Location: kernel/kprobes.c:2014
Inline: True
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
In kernel/kprobes.c (ffffffff811760fb)
Location: kernel/kprobes.c:2018
Inline: True
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
In kernel/kprobes.c (ffffffff81181fab)
Location: kernel/kprobes.c:2061
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kill_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81195d40)
Location: kernel/kprobes.c:2105
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_free_init_mem
```
**Symbols:**

```
ffffffff81195d40-ffffffff81195ea6: kill_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kill_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811929e0)
Location: kernel/kprobes.c:2132
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_free_init_mem
```
**Symbols:**

```
ffffffff811929e0-ffffffff81192b39: kill_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kill_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193900)
Location: kernel/kprobes.c:2137
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_free_init_mem
```
**Symbols:**

```
ffffffff81193900-ffffffff81193a77: kill_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kill_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:2131
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_free_init_mem
```
**Symbols:**

```
ffffffff811bc810-ffffffff811bc984: kill_kprobe (STB_LOCAL)
ffffffff81cb37cd-ffffffff81cb37e1: kill_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kill_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:2350
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_free_init_mem
```
**Symbols:**

```
ffffffff811ef870-ffffffff811ef9df: kill_kprobe (STB_LOCAL)
ffffffff81e6454e-ffffffff81e64563: kill_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void kill_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:2354
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_free_init_mem
```
**Symbols:**

```
ffffffff81236280-ffffffff81236404: kill_kprobe (STB_LOCAL)
ffffffff8205c658-ffffffff8205c66d: kill_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void kill_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:2367
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_free_init_mem
```
**Symbols:**

```
ffffffff8124d0a0-ffffffff8124d224: kill_kprobe (STB_LOCAL)
ffffffff820dafb5-ffffffff820dafca: kill_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void kill_kprobe(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:2352
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_free_init_mem
```
**Symbols:**

```
ffffffff81266fa0-ffffffff81267124: kill_kprobe (STB_LOCAL)
ffffffff821b6d0b-ffffffff821b6d20: kill_kprobe.cold (STB_LOCAL)
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
In kernel/kprobes.c (ffff8000101f75cc)
Location: kernel/kprobes.c:2061
Inline: True
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
In kernel/kprobes.c (c04376f8)
Location: kernel/kprobes.c:2061
Inline: True
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
In kernel/kprobes.c (c00000000026dbe0)
Location: kernel/kprobes.c:2061
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/kprobes.c (ffffffff8117a5cb)
Location: kernel/kprobes.c:2061
Inline: True
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
In kernel/kprobes.c (ffffffff8116d76b)
Location: kernel/kprobes.c:2061
Inline: True
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
In kernel/kprobes.c (ffffffff8117839b)
Location: kernel/kprobes.c:2061
Inline: True
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
In kernel/kprobes.c (ffffffff81185c6b)
Location: kernel/kprobes.c:2061
Inline: True
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
