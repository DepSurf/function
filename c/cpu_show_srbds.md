# Function: <code>cpu_show_srbds</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t cpu_show_srbds(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c780)
Location: arch/x86/kernel/cpu/bugs.c:1745
Inline: False
```
**Symbols:**

```
ffffffff8104c780-ffffffff8104c7db: cpu_show_srbds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t cpu_show_srbds(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104bca0)
Location: arch/x86/kernel/cpu/bugs.c:1753
Inline: False
```
**Symbols:**

```
ffffffff8104bca0-ffffffff8104bcfb: cpu_show_srbds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t cpu_show_srbds(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d7d0)
Location: arch/x86/kernel/cpu/bugs.c:1753
Inline: False
```
**Symbols:**

```
ffffffff8104d7d0-ffffffff8104d82b: cpu_show_srbds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t cpu_show_srbds(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054eb0)
Location: arch/x86/kernel/cpu/bugs.c:1924
Inline: False
```
**Symbols:**

```
ffffffff81054eb0-ffffffff81054f2c: cpu_show_srbds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t cpu_show_srbds(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060dd0)
Location: arch/x86/kernel/cpu/bugs.c:2483
Inline: False
```
**Symbols:**

```
ffffffff81060dd0-ffffffff81060e62: cpu_show_srbds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t cpu_show_srbds(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f630)
Location: arch/x86/kernel/cpu/bugs.c:2533
Inline: False
```
**Symbols:**

```
ffffffff8106f630-ffffffff8106f6b3: cpu_show_srbds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t cpu_show_srbds(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070ed0)
Location: arch/x86/kernel/cpu/bugs.c:2830
Inline: False
```
**Symbols:**

```
ffffffff81070ed0-ffffffff81070f53: cpu_show_srbds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t cpu_show_srbds(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810787f0)
Location: arch/x86/kernel/cpu/bugs.c:2993
Inline: False
```
**Symbols:**

```
ffffffff810787f0-ffffffff81078873: cpu_show_srbds (STB_GLOBAL)
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
