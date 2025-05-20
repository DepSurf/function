# Function: <code>__cleanup_nmi</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1887
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff8110b0a0-ffffffff8110b13d: __cleanup_nmi (STB_LOCAL)
ffffffff8110d6f7-ffffffff8110d70a: __cleanup_nmi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811172a0)
Location: kernel/irq/manage.c:1879
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff811172a0-ffffffff8111733d: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81122ba0)
Location: kernel/irq/manage.c:1918
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff81122ba0-ffffffff81122c3d: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111e9d0)
Location: kernel/irq/manage.c:1988
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff8111e9d0-ffffffff8111ea6d: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111eb10)
Location: kernel/irq/manage.c:1989
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff8111eb10-ffffffff8111ebad: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8113efa0)
Location: kernel/irq/manage.c:2018
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff8113efa0-ffffffff8113f03d: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81162620)
Location: kernel/irq/manage.c:2052
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff81162620-ffffffff811626c9: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81196150)
Location: kernel/irq/manage.c:2044
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff81196150-ffffffff811961f9: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a7b10)
Location: kernel/irq/manage.c:2050
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff811a7b10-ffffffff811a7bb9: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b7670)
Location: kernel/irq/manage.c:2047
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff811b7670-ffffffff811b7719: __cleanup_nmi (STB_LOCAL)
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
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff8000101790f0)
Location: kernel/irq/manage.c:1879
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffff8000101790f0-ffff8000101791a4: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cae6c)
Location: kernel/irq/manage.c:1879
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
c03cae6c-c03caf30: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d3b00)
Location: kernel/irq/manage.c:1879
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
c0000000001d3b00-c0000000001d3c04: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe0001140c8)
Location: kernel/irq/manage.c:1879
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffe0001140c8-ffffffe00011415e: __cleanup_nmi (STB_LOCAL)
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
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f880)
Location: kernel/irq/manage.c:1879
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff8110f880-ffffffff8110f91d: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811005c0)
Location: kernel/irq/manage.c:1879
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff811005c0-ffffffff8110065d: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d770)
Location: kernel/irq/manage.c:1879
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff8110d770-ffffffff8110d80d: __cleanup_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const void *__cleanup_nmi(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118cd0)
Location: kernel/irq/manage.c:1879
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
```
**Symbols:**

```
ffffffff81118cd0-ffffffff81118d6d: __cleanup_nmi (STB_LOCAL)
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
