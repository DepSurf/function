# Function: <code>jailhouse_setup_irq</code>

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
void jailhouse_setup_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff8108089e)
Location: arch/x86/kernel/jailhouse.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff8108089e-ffffffff810808f6: jailhouse_setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void jailhouse_setup_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff81bd8177)
Location: arch/x86/kernel/jailhouse.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81bd8177-ffffffff81bd81cf: jailhouse_setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void jailhouse_setup_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff81bc9fb1)
Location: arch/x86/kernel/jailhouse.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81bc9fb1-ffffffff81bca009: jailhouse_setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void jailhouse_setup_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff81c9f2c0)
Location: arch/x86/kernel/jailhouse.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81c9f2c0-ffffffff81c9f318: jailhouse_setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void jailhouse_setup_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff81e4ea0e)
Location: arch/x86/kernel/jailhouse.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81e4ea0e-ffffffff81e4ea70: jailhouse_setup_irq (STB_LOCAL)
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
In arch/x86/kernel/jailhouse.c (ffffffff810b918b)
Location: arch/x86/kernel/jailhouse.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
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
In arch/x86/kernel/jailhouse.c (ffffffff810bc35b)
Location: arch/x86/kernel/jailhouse.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
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
In arch/x86/kernel/jailhouse.c (ffffffff810c34db)
Location: arch/x86/kernel/jailhouse.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_serial_fixup
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
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
</ul>
