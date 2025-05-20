# Function: <code>irq_set_affinity_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dc090)
Location: kernel/irq/manage.c:210
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
```
**Symbols:**

```
ffffffff810dc090-ffffffff810dc18a: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e17a0)
Location: kernel/irq/manage.c:223
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
```
**Symbols:**

```
ffffffff810e17a0-ffffffff810e189b: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e8100)
Location: kernel/irq/manage.c:223
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
```
**Symbols:**

```
ffffffff810e8100-ffffffff810e81e7: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7560)
Location: kernel/irq/manage.c:197
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810e7560-ffffffff810e760c: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ef8d0)
Location: kernel/irq/manage.c:214
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810ef8d0-ffffffff810ef986: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f7cc0)
Location: kernel/irq/manage.c:247
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810f7cc0-ffffffff810f7db1: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81103410)
Location: kernel/irq/manage.c:247
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81103410-ffffffff81103501: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110be00)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8110be00-ffffffff8110bf11: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118200)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81118200-ffffffff81118342: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81123a20)
Location: kernel/irq/manage.c:347
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81123a20-ffffffff81123c11: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111f870)
Location: kernel/irq/manage.c:347
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8111f870-ffffffff8111fa61: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111fb30)
Location: kernel/irq/manage.c:347
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8111fb30-ffffffff8111fd1d: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8113ffd0)
Location: kernel/irq/manage.c:340
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8113ffd0-ffffffff811401bd: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811638d0)
Location: kernel/irq/manage.c:355
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811638d0-ffffffff81163ae1: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811975a0)
Location: kernel/irq/manage.c:347
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811975a0-ffffffff811977b1: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:350
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff820d802e-ffffffff820d808e: irq_set_affinity_locked.cold (STB_LOCAL)
ffffffff811a9140-ffffffff811a9478: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:352
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff821b32af-ffffffff821b330f: irq_set_affinity_locked.cold (STB_LOCAL)
ffffffff811b8ca0-ffffffff811b8fd8: irq_set_affinity_locked (STB_GLOBAL)
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
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017aa60)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
**Symbols:**

```
ffff80001017aa60-ffff80001017ab44: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cbcec)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
c03cbcec-c03cbdc4: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d4f50)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
c0000000001d4f50-c0000000001d50a4: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000114852)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
```
**Symbols:**

```
ffffffe000114852-ffffffe000114908: irq_set_affinity_locked (STB_GLOBAL)
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
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811107e0)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811107e0-ffffffff81110922: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81101510)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81101510-ffffffff81101652: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110e6d0)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8110e6d0-ffffffff8110e812: irq_set_affinity_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119c00)
Location: kernel/irq/manage.c:274
Inline: False
Direct callers:
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81119c00-ffffffff81119d42: irq_set_affinity_locked (STB_GLOBAL)
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
