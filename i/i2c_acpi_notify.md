# Function: <code>i2c_acpi_notify</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170b310)
Location: drivers/i2c/i2c-core.c:377
Inline: True
```
**Symbols:**

```
ffffffff8170b310-ffffffff8170b35d: i2c_acpi_notify.part.44 (STB_LOCAL)
ffffffff8170d9e0-ffffffff8170da9a: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817244f0)
Location: drivers/i2c/i2c-core-acpi.c:335
Inline: True
```
**Symbols:**

```
ffffffff817244f0-ffffffff8172453b: i2c_acpi_notify.part.5 (STB_LOCAL)
ffffffff81724540-ffffffff817245da: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817959c0)
Location: drivers/i2c/i2c-core-acpi.c:335
Inline: True
```
**Symbols:**

```
ffffffff817959c0-ffffffff81795a0b: i2c_acpi_notify.part.7 (STB_LOCAL)
ffffffff81795a10-ffffffff81795aaa: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8470)
Location: drivers/i2c/i2c-core-acpi.c:335
Inline: True
```
**Symbols:**

```
ffffffff817d8470-ffffffff817d84bb: i2c_acpi_notify.part.7 (STB_LOCAL)
ffffffff817d84c0-ffffffff817d855a: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff620)
Location: drivers/i2c/i2c-core-acpi.c:358
Inline: True
```
**Symbols:**

```
ffffffff817ff620-ffffffff817ff66b: i2c_acpi_notify.part.7 (STB_LOCAL)
ffffffff817ff670-ffffffff817ff70a: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81840770)
Location: drivers/i2c/i2c-core-acpi.c:381
Inline: True
```
**Symbols:**

```
ffffffff81840770-ffffffff818407bb: i2c_acpi_notify.part.0 (STB_LOCAL)
ffffffff818407c0-ffffffff81840875: i2c_acpi_notify (STB_LOCAL)
ffffffff81841117-ffffffff8184114c: i2c_acpi_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818720c0)
Location: drivers/i2c/i2c-core-acpi.c:410
Inline: True
```
**Symbols:**

```
ffffffff818720c0-ffffffff8187211f: i2c_acpi_notify.part.0 (STB_LOCAL)
ffffffff81872120-ffffffff818721d5: i2c_acpi_notify (STB_LOCAL)
ffffffff81872a90-ffffffff81872ac5: i2c_acpi_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:410
Inline: False
```
**Symbols:**

```
ffffffff81946430-ffffffff8194655e: i2c_acpi_notify (STB_LOCAL)
ffffffff81946c8c-ffffffff81946c9c: i2c_acpi_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:410
Inline: False
```
**Symbols:**

```
ffffffff8194c380-ffffffff8194c4b4: i2c_acpi_notify (STB_LOCAL)
ffffffff81c24e38-ffffffff81c24e48: i2c_acpi_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819302c0)
Location: drivers/i2c/i2c-core-acpi.c:406
Inline: False
```
**Symbols:**

```
ffffffff819302c0-ffffffff819303fa: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d3590)
Location: drivers/i2c/i2c-core-acpi.c:438
Inline: False
```
**Symbols:**

```
ffffffff819d3590-ffffffff819d36d6: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35c60)
Location: drivers/i2c/i2c-core-acpi.c:439
Inline: False
```
**Symbols:**

```
ffffffff81b35c60-ffffffff81b35de4: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccaee0)
Location: drivers/i2c/i2c-core-acpi.c:459
Inline: False
```
**Symbols:**

```
ffffffff81ccaee0-ffffffff81ccb05e: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32c80)
Location: drivers/i2c/i2c-core-acpi.c:448
Inline: False
```
**Symbols:**

```
ffffffff81d32c80-ffffffff81d32dc9: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8ca0)
Location: drivers/i2c/i2c-core-acpi.c:448
Inline: False
```
**Symbols:**

```
ffffffff81de8ca0-ffffffff81de8de9: i2c_acpi_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab5990)
Location: drivers/i2c/i2c-core-acpi.c:410
Inline: True
```
**Symbols:**

```
ffff800010ab5990-ffff800010ab5a04: i2c_acpi_notify.part.0 (STB_LOCAL)
ffff800010ab5a08-ffff800010ab5b08: i2c_acpi_notify (STB_LOCAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81866250)
Location: drivers/i2c/i2c-core-acpi.c:410
Inline: True
```
**Symbols:**

```
ffffffff81866250-ffffffff818662af: i2c_acpi_notify.part.0 (STB_LOCAL)
ffffffff818662b0-ffffffff81866365: i2c_acpi_notify (STB_LOCAL)
ffffffff81866c20-ffffffff81866c55: i2c_acpi_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_acpi_notify(struct notifier_block *nb, long unsigned int value, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81881500)
Location: drivers/i2c/i2c-core-acpi.c:410
Inline: True
```
**Symbols:**

```
ffffffff81881500-ffffffff8188155f: i2c_acpi_notify.part.0 (STB_LOCAL)
ffffffff81881560-ffffffff81881615: i2c_acpi_notify (STB_LOCAL)
ffffffff81881ed0-ffffffff81881f05: i2c_acpi_notify.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
