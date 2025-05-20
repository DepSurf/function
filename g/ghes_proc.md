# Function: <code>ghes_proc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff814b67f0)
Location: drivers/acpi/apei/ghes.c:646
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_sci
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff814b67f0-ffffffff814b685b: ghes_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815061d0)
Location: drivers/acpi/apei/ghes.c:651
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_sci
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff815061d0-ffffffff8150623b: ghes_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8152a3e0)
Location: drivers/acpi/apei/ghes.c:651
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_sci
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff8152a3e0-ffffffff8152a453: ghes_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8153cf00)
Location: drivers/acpi/apei/ghes.c:728
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff8153cf00-ffffffff8153d02c: ghes_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8159fab0)
Location: drivers/acpi/apei/ghes.c:684
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff8159fab0-ffffffff8159fc0a: ghes_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815d7710)
Location: drivers/acpi/apei/ghes.c:700
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff815d7710-ffffffff815d7845: ghes_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815f0e90)
Location: drivers/acpi/apei/ghes.c:715
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff815f0e90-ffffffff815f0fcc: ghes_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:707
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff81622c60-ffffffff81622dda: ghes_proc (STB_LOCAL)
ffffffff81623483-ffffffff81623488: ghes_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:720
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff81644730-ffffffff816448aa: ghes_proc (STB_LOCAL)
ffffffff81644f72-ffffffff81644f77: ghes_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:744
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff816f1990-ffffffff816f1b2a: ghes_proc (STB_LOCAL)
ffffffff816f2540-ffffffff816f2557: ghes_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:807
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff8170ed50-ffffffff8170eeea: ghes_proc (STB_LOCAL)
ffffffff81c03794-ffffffff81c037ab: ghes_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:854
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff816f0630-ffffffff816f07ca: ghes_proc (STB_LOCAL)
ffffffff81bf51b5-ffffffff81bf51cc: ghes_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:854
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff8176a740-ffffffff8176a8da: ghes_proc (STB_LOCAL)
ffffffff81cf2630-ffffffff81cf2647: ghes_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:854
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff8189f2c0-ffffffff8189f470: ghes_proc (STB_LOCAL)
ffffffff81eba778-ffffffff81eba789: ghes_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e8530)
Location: drivers/acpi/apei/ghes.c:876
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff819e8530-ffffffff819e86ea: ghes_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a30db0)
Location: drivers/acpi/apei/ghes.c:874
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff81a30db0-ffffffff81a30f6a: ghes_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7c220)
Location: drivers/acpi/apei/ghes.c:912
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff81a7c220-ffffffff81a7c3de: ghes_proc (STB_LOCAL)
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
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffff8000107b0100)
Location: drivers/acpi/apei/ghes.c:720
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffff8000107b0100-ffff8000107b0264: ghes_proc (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:720
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff81638570-ffffffff816386ea: ghes_proc (STB_LOCAL)
ffffffff81638db2-ffffffff81638db7: ghes_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ghes_proc(struct ghes *ghes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:720
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
**Symbols:**

```
ffffffff816528b0-ffffffff81652a2a: ghes_proc (STB_LOCAL)
ffffffff81653102-ffffffff81653107: ghes_proc.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
