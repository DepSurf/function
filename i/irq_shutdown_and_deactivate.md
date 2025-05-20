# Function: <code>irq_shutdown_and_deactivate</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110eee0)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8110eee0-ffffffff8110ef0b: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b1a0)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8111b1a0-ffffffff8111b1cb: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81127350)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81127350-ffffffff81127371: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122f50)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81122f50-ffffffff81122f71: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123250)
Location: kernel/irq/chip.c:323
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81123250-ffffffff81123271: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143820)
Location: kernel/irq/chip.c:323
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81143820-ffffffff81143841: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811675e0)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff811675e0-ffffffff81167607: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119b980)
Location: kernel/irq/chip.c:322
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff8119b980-ffffffff8119b9a7: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ad760)
Location: kernel/irq/chip.c:323
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff811ad760-ffffffff811ad7ff: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bd360)
Location: kernel/irq/chip.c:323
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff811bd360-ffffffff811bd3ff: irq_shutdown_and_deactivate (STB_GLOBAL)
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
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017f0e0)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffff80001017f0e0-ffff80001017f120: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03cf2d8)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
c03cf2d8-c03cf310: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d99b0)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
c0000000001d99b0-c0000000001d9a1c: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001176b8)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
```
**Symbols:**

```
ffffffe0001176b8-ffffffe0001176fa: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81113780)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81113780-ffffffff811137ab: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104490)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81104490-ffffffff811044bb: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81111670)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81111670-ffffffff8111169b: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111cc30)
Location: kernel/irq/chip.c:320
Inline: False
Direct callers:
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8111cc30-ffffffff8111cc5b: irq_shutdown_and_deactivate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
