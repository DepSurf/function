# Function: <code>rcutree_migrate_callbacks</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81100a50)
Location: kernel/rcu/tree.c:3998
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81100a50-ffffffff81100baa: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811088e0)
Location: kernel/rcu/tree.c:3796
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff811088e0-ffffffff81108ab6: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113d70)
Location: kernel/rcu/tree.c:3467
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81113d70-ffffffff81113f13: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d990)
Location: kernel/rcu/tree.c:3150
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff8111d990-ffffffff8111db46: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129f30)
Location: kernel/rcu/tree.c:3205
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81129f30-ffffffff8112a0e7: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81138390)
Location: kernel/rcu/tree.c:3928
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81138390-ffffffff811385b3: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133c50)
Location: kernel/rcu/tree.c:4249
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81133c50-ffffffff81133e8f: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811348e0)
Location: kernel/rcu/tree.c:4364
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff811348e0-ffffffff81134b1f: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4335
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81caf62b-ffffffff81caf640: rcutree_migrate_callbacks.cold (STB_LOCAL)
ffffffff81157050-ffffffff811572c5: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4461
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81e602cf-ffffffff81e602e4: rcutree_migrate_callbacks.cold (STB_LOCAL)
ffffffff81180150-ffffffff81180403: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4354
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff8205a36f-ffffffff8205a384: rcutree_migrate_callbacks.cold (STB_LOCAL)
ffffffff811ba640-ffffffff811ba8d1: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4512
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff820d8b9d-ffffffff820d8bb2: rcutree_migrate_callbacks.cold (STB_LOCAL)
ffffffff811ccf80-ffffffff811cd21b: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4614
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff821b42ae-ffffffff821b42c3: rcutree_migrate_callbacks.cold (STB_LOCAL)
ffffffff811e1950-ffffffff811e1cd9: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010191d70)
Location: kernel/rcu/tree.c:3205
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffff800010191d70-ffff800010191f7c: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03df780)
Location: kernel/rcu/tree.c:3205
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
c03df780-c03df9a0: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ed300)
Location: kernel/rcu/tree.c:3205
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
c0000000001ed300-c0000000001ed588: rcutree_migrate_callbacks (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81122510)
Location: kernel/rcu/tree.c:3205
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81122510-ffffffff811226c7: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114bc0)
Location: kernel/rcu/tree.c:3205
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81114bc0-ffffffff81114dc0: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81120400)
Location: kernel/rcu/tree.c:3205
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff81120400-ffffffff811205b7: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcutree_migrate_callbacks(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112c660)
Location: kernel/rcu/tree.c:3205
Inline: False
Direct callers:
  - kernel/cpu.c:takedown_cpu
```
**Symbols:**

```
ffffffff8112c660-ffffffff8112c815: rcutree_migrate_callbacks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
