# Function: <code>cec_notifier</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cec_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff819d9950)
Location: drivers/ras/cec.c:530
Inline: True
```
**Symbols:**

```
ffffffff819d9950-ffffffff819d99ae: cec_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cec_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff819d8ca0)
Location: drivers/ras/cec.c:519
Inline: True
```
**Symbols:**

```
ffffffff819d8ca0-ffffffff819d8cfe: cec_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cec_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff819bee00)
Location: drivers/ras/cec.c:528
Inline: True
```
**Symbols:**

```
ffffffff819bee00-ffffffff819bee5e: cec_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cec_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81a6e390)
Location: drivers/ras/cec.c:528
Inline: True
```
**Symbols:**

```
ffffffff81a6e390-ffffffff81a6e3ee: cec_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cec_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81bdf250)
Location: drivers/ras/cec.c:528
Inline: False
```
**Symbols:**

```
ffffffff81bdf250-ffffffff81bdf2be: cec_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cec_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81d8a810)
Location: drivers/ras/cec.c:528
Inline: False
```
**Symbols:**

```
ffffffff81d8a810-ffffffff81d8a87e: cec_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cec_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81df8e10)
Location: drivers/ras/cec.c:528
Inline: False
```
**Symbols:**

```
ffffffff81df8e10-ffffffff81df8e7e: cec_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cec_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81eaf4d0)
Location: drivers/ras/cec.c:528
Inline: False
```
**Symbols:**

```
ffffffff81eaf4d0-ffffffff81eaf53e: cec_notifier (STB_LOCAL)
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
