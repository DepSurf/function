# Function: <code>devm_i2c_release_dummy</code>

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
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183b750)
Location: drivers/i2c/i2c-core-base.c:928
Inline: False
```
**Symbols:**

```
ffffffff8183b750-ffffffff8183b772: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186d0e0)
Location: drivers/i2c/i2c-core-base.c:933
Inline: False
```
**Symbols:**

```
ffffffff8186d0e0-ffffffff8186d102: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81940ea0)
Location: drivers/i2c/i2c-core-base.c:895
Inline: False
```
**Symbols:**

```
ffffffff81940ea0-ffffffff81940ec2: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81947270)
Location: drivers/i2c/i2c-core-base.c:1023
Inline: False
```
**Symbols:**

```
ffffffff81947270-ffffffff81947292: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_i2c_release_dummy(void *client);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192cccc)
Location: drivers/i2c/i2c-core-base.c:1063
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
**Symbols:**

```
ffffffff8192ab80-ffffffff8192ab9f: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void devm_i2c_release_dummy(void *client);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cfe9c)
Location: drivers/i2c/i2c-core-base.c:1064
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
**Symbols:**

```
ffffffff819cdd30-ffffffff819cdd4f: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void devm_i2c_release_dummy(void *client);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b31d9c)
Location: drivers/i2c/i2c-core-base.c:1066
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
**Symbols:**

```
ffffffff81b2eb40-ffffffff81b2eb56: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devm_i2c_release_dummy(void *client);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc69bc)
Location: drivers/i2c/i2c-core-base.c:1060
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
**Symbols:**

```
ffffffff81cc27f0-ffffffff81cc2806: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devm_i2c_release_dummy(void *client);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2e663)
Location: drivers/i2c/i2c-core-base.c:1104
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
**Symbols:**

```
ffffffff81d2a210-ffffffff81d2a226: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devm_i2c_release_dummy(void *client);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de4613)
Location: drivers/i2c/i2c-core-base.c:1112
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
**Symbols:**

```
ffffffff81de00d0-ffffffff81de00e6: devm_i2c_release_dummy (STB_LOCAL)
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
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab0358)
Location: drivers/i2c/i2c-core-base.c:933
Inline: False
```
**Symbols:**

```
ffff800010ab0358-ffff800010ab0390: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b91984)
Location: drivers/i2c/i2c-core-base.c:933
Inline: False
```
**Symbols:**

```
c0b91984-c0b919b4: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b932b0)
Location: drivers/i2c/i2c-core-base.c:933
Inline: False
```
**Symbols:**

```
c000000000b932b0-c000000000b932dc: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b854a)
Location: drivers/i2c/i2c-core-base.c:933
Inline: False
```
**Symbols:**

```
ffffffe0006b854a-ffffffe0006b857c: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
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
<summary>In <code>gcp</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81861270)
Location: drivers/i2c/i2c-core-base.c:933
Inline: False
```
**Symbols:**

```
ffffffff81861270-ffffffff81861292: devm_i2c_release_dummy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187c480)
Location: drivers/i2c/i2c-core-base.c:933
Inline: False
```
**Symbols:**

```
ffffffff8187c480-ffffffff8187c4a2: devm_i2c_release_dummy (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *client</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>void *res</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
