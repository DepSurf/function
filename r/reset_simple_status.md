# Function: <code>reset_simple_status</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reset_simple_status(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/reset-simple.c (0)
Location: drivers/reset/reset-simple.c:85
Inline: False
```
**Symbols:**

```
ffffffff81a47860-ffffffff81a478b4: reset_simple_status (STB_LOCAL)
ffffffff82094f4d-ffffffff82094f68: reset_simple_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reset_simple_status(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/reset-simple.c (0)
Location: drivers/reset/reset-simple.c:85
Inline: False
```
**Symbols:**

```
ffffffff81a91a10-ffffffff81a91a60: reset_simple_status (STB_LOCAL)
ffffffff82115d72-ffffffff82115d86: reset_simple_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reset_simple_status(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/reset-simple.c (0)
Location: drivers/reset/reset-simple.c:84
Inline: False
```
**Symbols:**

```
ffffffff81ae43a0-ffffffff81ae43f0: reset_simple_status (STB_LOCAL)
ffffffff821f3a79-ffffffff821f3a8d: reset_simple_status.cold (STB_LOCAL)
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
int reset_simple_status(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/reset-simple.c (ffff80001084df78)
Location: drivers/reset/reset-simple.c:67
Inline: False
```
**Symbols:**

```
ffff80001084df78-ffff80001084dfdc: reset_simple_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reset_simple_status(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/reset-simple.c (c0959f9c)
Location: drivers/reset/reset-simple.c:67
Inline: False
```
**Symbols:**

```
c0959f9c-c0959fe0: reset_simple_status (STB_LOCAL)
```
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
