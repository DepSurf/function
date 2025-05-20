# Function: <code>clocksource_verify_choose_cpus</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void clocksource_verify_choose_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:271
Inline: False
```
**Symbols:**

```
ffffffff8116d750-ffffffff8116d89d: clocksource_verify_choose_cpus (STB_LOCAL)
ffffffff81cb184d-ffffffff81cb1865: clocksource_verify_choose_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void clocksource_verify_choose_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:277
Inline: False
```
**Symbols:**

```
ffffffff811a1840-ffffffff811a19cc: clocksource_verify_choose_cpus (STB_LOCAL)
ffffffff81e62df8-ffffffff81e62e10: clocksource_verify_choose_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clocksource_verify_choose_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811e09f0)
Location: kernel/time/clocksource.c:277
Inline: False
```
**Symbols:**

```
ffffffff811e09f0-ffffffff811e0b9e: clocksource_verify_choose_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clocksource_verify_choose_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811f4f50)
Location: kernel/time/clocksource.c:280
Inline: False
```
**Symbols:**

```
ffffffff811f4f50-ffffffff811f50fe: clocksource_verify_choose_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clocksource_verify_choose_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8120b0f0)
Location: kernel/time/clocksource.c:282
Inline: False
```
**Symbols:**

```
ffffffff8120b0f0-ffffffff8120b29e: clocksource_verify_choose_cpus (STB_LOCAL)
```
</details>
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
