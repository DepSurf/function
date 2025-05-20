# Function: <code>linereq_free</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void linereq_free(struct linereq *lr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a810)
Location: drivers/gpio/gpiolib-cdev.c:1278
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_release
```
**Symbols:**

```
ffffffff8163a810-ffffffff8163a8ff: linereq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void linereq_free(struct linereq *lr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161e3a0)
Location: drivers/gpio/gpiolib-cdev.c:1278
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_release
```
**Symbols:**

```
ffffffff8161e3a0-ffffffff8161e48f: linereq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void linereq_free(struct linereq *lr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d960)
Location: drivers/gpio/gpiolib-cdev.c:1278
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_release
```
**Symbols:**

```
ffffffff8168d960-ffffffff8168da4f: linereq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void linereq_free(struct linereq *lr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac7a0)
Location: drivers/gpio/gpiolib-cdev.c:1464
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_release
```
**Symbols:**

```
ffffffff817ac7a0-ffffffff817ac853: linereq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void linereq_free(struct linereq *lr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5750)
Location: drivers/gpio/gpiolib-cdev.c:1567
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_release
```
**Symbols:**

```
ffffffff818c5750-ffffffff818c57d4: linereq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void linereq_free(struct linereq *lr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908800)
Location: drivers/gpio/gpiolib-cdev.c:1566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_release
```
**Symbols:**

```
ffffffff81908800-ffffffff8190888d: linereq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void linereq_free(struct linereq *lr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951870)
Location: drivers/gpio/gpiolib-cdev.c:1624
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_release
```
**Symbols:**

```
ffffffff81951870-ffffffff8195195f: linereq_free (STB_LOCAL)
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
