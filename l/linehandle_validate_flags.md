# Function: <code>linehandle_validate_flags</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int linehandle_validate_flags(u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160c350)
Location: drivers/gpio/gpiolib.c:456
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_set_config
```
**Symbols:**

```
ffffffff8160c350-ffffffff8160c3b6: linehandle_validate_flags (STB_LOCAL)
```
</details>
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
int linehandle_validate_flags(u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aa200)
Location: drivers/gpio/gpiolib-cdev.c:87
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
```
**Symbols:**

```
ffffffff817aa200-ffffffff817aa27b: linehandle_validate_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int linehandle_validate_flags(u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c2da0)
Location: drivers/gpio/gpiolib-cdev.c:133
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
```
**Symbols:**

```
ffffffff818c2da0-ffffffff818c2e1b: linehandle_validate_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int linehandle_validate_flags(u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81905c60)
Location: drivers/gpio/gpiolib-cdev.c:133
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
```
**Symbols:**

```
ffffffff81905c60-ffffffff81905cec: linehandle_validate_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int linehandle_validate_flags(u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194d670)
Location: drivers/gpio/gpiolib-cdev.c:98
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
```
**Symbols:**

```
ffffffff8194d670-ffffffff8194d6fc: linehandle_validate_flags (STB_LOCAL)
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
