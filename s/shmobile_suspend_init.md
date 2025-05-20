# Function: <code>shmobile_suspend_init</code>

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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmobile_suspend_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mach-shmobile/suspend.c (c151a234)
Location: arch/arm/mach-shmobile/suspend.c:43
Inline: False
Direct callers:
  - arch/arm/mach-shmobile/setup-sh73a0.c:shmobile_init_late
  - arch/arm/mach-shmobile/setup-r8a7740.c:shmobile_init_late
  - arch/arm/mach-shmobile/setup-r8a7778.c:shmobile_init_late
  - arch/arm/mach-shmobile/setup-r8a7779.c:shmobile_init_late
  - arch/arm/mach-shmobile/setup-emev2.c:shmobile_init_late
  - arch/arm/mach-shmobile/setup-r7s72100.c:shmobile_init_late
  - arch/arm/mach-shmobile/setup-r7s9210.c:shmobile_init_late
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:shmobile_init_late
```
**Symbols:**

```
c151a234-c151a25c: shmobile_suspend_init (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
