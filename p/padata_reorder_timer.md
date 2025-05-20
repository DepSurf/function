# Function: <code>padata_reorder_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void padata_reorder_timer(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81189df0)
Location: kernel/padata.c:285
Inline: False
```
**Symbols:**

```
ffffffff81189df0-ffffffff81189e00: padata_reorder_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void padata_reorder_timer(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8119c4f0)
Location: kernel/padata.c:285
Inline: False
```
**Symbols:**

```
ffffffff8119c4f0-ffffffff8119c500: padata_reorder_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void padata_reorder_timer(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811ac2d0)
Location: kernel/padata.c:282
Inline: False
```
**Symbols:**

```
ffffffff811ac2d0-ffffffff811ac2e0: padata_reorder_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void padata_reorder_timer(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811b3900)
Location: kernel/padata.c:278
Inline: False
```
**Symbols:**

```
ffffffff811b3900-ffffffff811b3910: padata_reorder_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void padata_reorder_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811c7d00)
Location: kernel/padata.c:291
Inline: False
```
**Symbols:**

```
ffffffff811c7d00-ffffffff811c7d74: padata_reorder_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void padata_reorder_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811e8110)
Location: kernel/padata.c:292
Inline: False
```
**Symbols:**

```
ffffffff811e8110-ffffffff811e8184: padata_reorder_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void padata_reorder_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811f8e60)
Location: kernel/padata.c:292
Inline: False
```
**Symbols:**

```
ffffffff811f8e60-ffffffff811f8ed4: padata_reorder_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void padata_reorder_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81210150)
Location: kernel/padata.c:297
Inline: False
```
**Symbols:**

```
ffffffff81210150-ffffffff812101bf: padata_reorder_timer (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct timer_list *t</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int arg</code>
</li>
</ul>
</details>
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
</ul>
