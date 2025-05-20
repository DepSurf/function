# Function: <code>__printk_safe_flush</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810e4b90)
Location: kernel/printk/printk_safe.c:192
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff810e4b90-ffffffff810e4dc4: __printk_safe_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810ece30)
Location: kernel/printk/printk_safe.c:189
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff810ece30-ffffffff810ed026: __printk_safe_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:192
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff810f5210-ffffffff810f5371: __printk_safe_flush (STB_LOCAL)
ffffffff810f55d5-ffffffff810f5674: __printk_safe_flush.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:192
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff811009c0-ffffffff81100b11: __printk_safe_flush (STB_LOCAL)
ffffffff81100d7c-ffffffff81100e0d: __printk_safe_flush.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff811091b0-ffffffff811092d4: __printk_safe_flush (STB_LOCAL)
ffffffff8110951c-ffffffff81109606: __printk_safe_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff81115590-ffffffff811156b4: __printk_safe_flush (STB_LOCAL)
ffffffff811158ec-ffffffff811159d6: __printk_safe_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:181
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff81120ef0-ffffffff81120f96: __printk_safe_flush (STB_LOCAL)
ffffffff81121350-ffffffff81121377: __printk_safe_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:183
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff8111bb50-ffffffff8111bbf6: __printk_safe_flush (STB_LOCAL)
ffffffff81be14de-ffffffff81be1505: __printk_safe_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:183
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff8111bf40-ffffffff8111c062: __printk_safe_flush (STB_LOCAL)
ffffffff81bd34f4-ffffffff81bd35ae: __printk_safe_flush.cold (STB_LOCAL)
```
</details>
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
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffff800010176938)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffff800010176938-ffff800010176bfc: __printk_safe_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c03c88c8)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
c03c88c8-c03c8b0c: __printk_safe_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c0000000001d02c0)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
c0000000001d02c0-c0000000001d0578: __printk_safe_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffe000111c3e)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffe000111c3e-ffffffe000111e1c: __printk_safe_flush (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff8110db70-ffffffff8110dc94: __printk_safe_flush (STB_LOCAL)
ffffffff8110decc-ffffffff8110dfb6: __printk_safe_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff810fe8d0-ffffffff810fe9f4: __printk_safe_flush (STB_LOCAL)
ffffffff810fec2c-ffffffff810fed16: __printk_safe_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff8110ba60-ffffffff8110bb84: __printk_safe_flush (STB_LOCAL)
ffffffff8110bdbc-ffffffff8110bea6: __printk_safe_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __printk_safe_flush(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:180
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush
```
**Symbols:**

```
ffffffff81116f70-ffffffff81117094: __printk_safe_flush (STB_LOCAL)
ffffffff811172ee-ffffffff811173d8: __printk_safe_flush.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
