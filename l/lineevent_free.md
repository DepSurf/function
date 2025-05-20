# Function: <code>lineevent_free</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lineevent_free(struct lineevent_state *le);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ab750)
Location: drivers/gpio/gpiolib-cdev.c:1771
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_release
```
**Symbols:**

```
ffffffff817ab750-ffffffff817ab7a9: lineevent_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lineevent_free(struct lineevent_state *le);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4560)
Location: drivers/gpio/gpiolib-cdev.c:1912
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_release
```
**Symbols:**

```
ffffffff818c4560-ffffffff818c45b5: lineevent_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lineevent_free(struct lineevent_state *le);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907630)
Location: drivers/gpio/gpiolib-cdev.c:1910
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_release
```
**Symbols:**

```
ffffffff81907630-ffffffff81907685: lineevent_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lineevent_free(struct lineevent_state *le);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194ee70)
Location: drivers/gpio/gpiolib-cdev.c:1976
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_release
```
**Symbols:**

```
ffffffff8194ee70-ffffffff8194eedf: lineevent_free (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
