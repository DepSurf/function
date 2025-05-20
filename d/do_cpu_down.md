# Function: <code>do_cpu_down</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084720)
Location: kernel/cpu.c:855
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff81084720-ffffffff81084773: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810896c0)
Location: kernel/cpu.c:816
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff810896c0-ffffffff81089713: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086720)
Location: kernel/cpu.c:739
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff81086720-ffffffff8108676f: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108d4d0)
Location: kernel/cpu.c:914
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff8108d4d0-ffffffff8108d51f: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81090e00)
Location: kernel/cpu.c:1007
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff81090e00-ffffffff81090e4f: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81098f50)
Location: kernel/cpu.c:1023
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff81098f50-ffffffff81098f9f: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d4d0)
Location: kernel/cpu.c:1035
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff8109d4d0-ffffffff8109d526: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3a20)
Location: kernel/cpu.c:1044
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff810a3a20-ffffffff810a3a76: do_cpu_down (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9338)
Location: kernel/cpu.c:1044
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffff8000100f9338-ffff8000100f93ac: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0357648)
Location: kernel/cpu.c:1044
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
c0357648-c03576b0: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0000000001400d0)
Location: kernel/cpu.c:1044
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
c0000000001400d0-c000000000140178: do_cpu_down (STB_LOCAL)
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
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d340)
Location: kernel/cpu.c:1044
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff8109d340-ffffffff8109d396: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bd60)
Location: kernel/cpu.c:1044
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff8108bd60-ffffffff8108bdb6: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d2f0)
Location: kernel/cpu.c:1044
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff8109d2f0-ffffffff8109d346: do_cpu_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_cpu_down(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5170)
Location: kernel/cpu.c:1044
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_down
```
**Symbols:**

```
ffffffff810a5170-ffffffff810a51c6: do_cpu_down (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
