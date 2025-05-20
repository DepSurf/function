# Function: <code>irq_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810de130)
Location: kernel/irq/chip.c:208
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff810de130-ffffffff810de199: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e3a80)
Location: kernel/irq/chip.c:208
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff810e3a80-ffffffff810e3ae9: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea2d0)
Location: kernel/irq/chip.c:207
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff810ea2d0-ffffffff810ea336: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9900)
Location: kernel/irq/chip.c:283
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810e9900-ffffffff810e9973: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f1dd0)
Location: kernel/irq/chip.c:306
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810f1dd0-ffffffff810f1e46: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fa210)
Location: kernel/irq/chip.c:304
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810fa210-ffffffff810fa286: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811059d0)
Location: kernel/irq/chip.c:304
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff811059d0-ffffffff81105a46: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110eee5)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff8110e590-ffffffff8110e5f5: irq_shutdown.part.0 (STB_LOCAL)
ffffffff8110eec0-ffffffff8110eede: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b1a5)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff8111a850-ffffffff8111a8b5: irq_shutdown.part.0 (STB_LOCAL)
ffffffff8111b180-ffffffff8111b19e: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81127280)
Location: kernel/irq/chip.c:304
Inline: True
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff81127280-ffffffff8112734e: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122e80)
Location: kernel/irq/chip.c:304
Inline: True
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff81122e80-ffffffff81122f4e: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123180)
Location: kernel/irq/chip.c:307
Inline: True
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff81123180-ffffffff8112324e: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143750)
Location: kernel/irq/chip.c:307
Inline: True
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff81143750-ffffffff8114381e: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811674f0)
Location: kernel/irq/chip.c:304
Inline: True
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff811674f0-ffffffff811675d9: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119b880)
Location: kernel/irq/chip.c:306
Inline: True
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff8119b880-ffffffff8119b969: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ad765)
Location: kernel/irq/chip.c:306
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff811ad6c0-ffffffff811ad747: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bd365)
Location: kernel/irq/chip.c:306
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff811bd2c0-ffffffff811bd347: irq_shutdown (STB_GLOBAL)
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
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffff80001017f0f8)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffff80001017df98-ffff80001017e02c: irq_shutdown.part.0 (STB_LOCAL)
ffff80001017f0a8-ffff80001017f0e0: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (c03cf2ec)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
c03ce884-c03ce8f8: irq_shutdown.part.0 (STB_LOCAL)
c03cf2ac-c03cf2d8: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (c0000000001d99c0)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
c0000000001d8b50-c0000000001d8c1c: irq_shutdown.part.0 (STB_LOCAL)
c0000000001d9980-c0000000001d99a4: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001176ce)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffe000116aa6-ffffffe000116b08: irq_shutdown.part.0 (STB_LOCAL)
ffffffe000117682-ffffffe0001176b8: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff81113785)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff81112e30-ffffffff81112e95: irq_shutdown.part.0 (STB_LOCAL)
ffffffff81113760-ffffffff8111377e: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104495)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff81103b50-ffffffff81103bb5: irq_shutdown.part.0 (STB_LOCAL)
ffffffff81104470-ffffffff8110448e: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff81111675)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff81110d20-ffffffff81110d85: irq_shutdown.part.0 (STB_LOCAL)
ffffffff81111650-ffffffff8111166e: irq_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_shutdown(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111cc35)
Location: kernel/irq/chip.c:304
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff8111c4f0-ffffffff8111c555: irq_shutdown.part.0 (STB_LOCAL)
ffffffff8111cc10-ffffffff8111cc2e: irq_shutdown (STB_GLOBAL)
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
