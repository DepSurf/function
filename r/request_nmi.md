# Function: <code>request_nmi</code>

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
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2134
Inline: False
```
**Symbols:**

```
ffffffff8110d8fb-ffffffff8110d914: request_nmi.cold (STB_LOCAL)
ffffffff8110d160-ffffffff8110d301: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119550)
Location: kernel/irq/manage.c:2126
Inline: False
```
**Symbols:**

```
ffffffff81119550-ffffffff811196fe: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81124df0)
Location: kernel/irq/manage.c:2165
Inline: False
```
**Symbols:**

```
ffffffff81124df0-ffffffff81124fbb: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81120c50)
Location: kernel/irq/manage.c:2235
Inline: False
```
**Symbols:**

```
ffffffff81120c50-ffffffff81120e1b: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81120f20)
Location: kernel/irq/manage.c:2241
Inline: False
```
**Symbols:**

```
ffffffff81120f20-ffffffff811210f3: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811414a0)
Location: kernel/irq/manage.c:2270
Inline: False
```
**Symbols:**

```
ffffffff811414a0-ffffffff81141673: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81164ec0)
Location: kernel/irq/manage.c:2304
Inline: False
```
**Symbols:**

```
ffffffff81164ec0-ffffffff8116508b: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81198d10)
Location: kernel/irq/manage.c:2296
Inline: False
```
**Symbols:**

```
ffffffff81198d10-ffffffff81198edb: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811aa9f0)
Location: kernel/irq/manage.c:2302
Inline: False
```
**Symbols:**

```
ffffffff811aa9f0-ffffffff811aabbb: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ba5d0)
Location: kernel/irq/manage.c:2299
Inline: False
```
**Symbols:**

```
ffffffff811ba5d0-ffffffff811ba7ca: request_nmi (STB_GLOBAL)
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
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017c120)
Location: kernel/irq/manage.c:2126
Inline: False
```
**Symbols:**

```
ffff80001017c120-ffff80001017c358: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cd160)
Location: kernel/irq/manage.c:2126
Inline: False
```
**Symbols:**

```
c03cd160-c03cd318: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d6c90)
Location: kernel/irq/manage.c:2126
Inline: False
```
**Symbols:**

```
c0000000001d6c90-c0000000001d6f10: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe0001158cc)
Location: kernel/irq/manage.c:2126
Inline: False
```
**Symbols:**

```
ffffffe0001158cc-ffffffe000115a3e: request_nmi (STB_GLOBAL)
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
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81111b30)
Location: kernel/irq/manage.c:2126
Inline: False
```
**Symbols:**

```
ffffffff81111b30-ffffffff81111cde: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102860)
Location: kernel/irq/manage.c:2126
Inline: False
```
**Symbols:**

```
ffffffff81102860-ffffffff81102a0e: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110fa20)
Location: kernel/irq/manage.c:2126
Inline: False
```
**Symbols:**

```
ffffffff8110fa20-ffffffff8110fbce: request_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int request_nmi(unsigned int irq, irq_handler_t handler, long unsigned int irqflags, const char *name, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111af50)
Location: kernel/irq/manage.c:2126
Inline: False
```
**Symbols:**

```
ffffffff8111af50-ffffffff8111b0fe: request_nmi (STB_GLOBAL)
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
