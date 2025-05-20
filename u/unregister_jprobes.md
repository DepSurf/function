# Function: <code>unregister_jprobes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_jprobes(struct jprobe **jps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8112e290)
Location: kernel/kprobes.c:1761
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_jprobe
  - kernel/kprobes.c:register_jprobes
Direct callers:
  - kernel/kprobes.c:unregister_jprobe
  - kernel/kprobes.c:register_jprobes
```
**Symbols:**

```
ffffffff8112e290-ffffffff8112e332: unregister_jprobes.part.21 (STB_LOCAL)
ffffffff8112e340-ffffffff8112e355: unregister_jprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_jprobes(struct jprobe **jps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811365d6)
Location: kernel/kprobes.c:1761
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_jprobe
  - kernel/kprobes.c:register_jprobes
Direct callers:
  - kernel/kprobes.c:unregister_jprobe
  - kernel/kprobes.c:register_jprobes
```
**Symbols:**

```
ffffffff81136510-ffffffff811365ad: unregister_jprobes.part.23 (STB_LOCAL)
ffffffff811365b0-ffffffff811365c5: unregister_jprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_jprobes(struct jprobe **jps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81140356)
Location: kernel/kprobes.c:1761
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_jprobe
  - kernel/kprobes.c:register_jprobes
Direct callers:
  - kernel/kprobes.c:unregister_jprobe
  - kernel/kprobes.c:register_jprobes
```
**Symbols:**

```
ffffffff81140290-ffffffff8114032d: unregister_jprobes.part.25 (STB_LOCAL)
ffffffff81140330-ffffffff81140345: unregister_jprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_jprobes(struct jprobe **jps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811416e6)
Location: kernel/kprobes.c:1821
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_jprobe
Direct callers:
  - kernel/kprobes.c:unregister_jprobe
```
**Symbols:**

```
ffffffff81141620-ffffffff811416b7: unregister_jprobes.part.23 (STB_LOCAL)
ffffffff811416c0-ffffffff811416d6: unregister_jprobes (STB_GLOBAL)
```
</details>
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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
