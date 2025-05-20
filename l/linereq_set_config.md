# Function: <code>linereq_set_config</code>

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
long int linereq_set_config(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163ae30)
Location: drivers/gpio/gpiolib-cdev.c:1164
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff8163ae30-ffffffff8163af0c: linereq_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int linereq_set_config(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f150)
Location: drivers/gpio/gpiolib-cdev.c:1164
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff8161f150-ffffffff8161f1fb: linereq_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int linereq_set_config(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168dea0)
Location: drivers/gpio/gpiolib-cdev.c:1164
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff8168dea0-ffffffff8168df4b: linereq_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int linereq_set_config(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac6e0)
Location: drivers/gpio/gpiolib-cdev.c:1348
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff817ac6e0-ffffffff817ac79d: linereq_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int linereq_set_config(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5680)
Location: drivers/gpio/gpiolib-cdev.c:1418
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_unlocked
```
**Symbols:**

```
ffffffff818c5680-ffffffff818c573d: linereq_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int linereq_set_config(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908730)
Location: drivers/gpio/gpiolib-cdev.c:1417
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_unlocked
```
**Symbols:**

```
ffffffff81908730-ffffffff819087ed: linereq_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int linereq_set_config(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194fcf0)
Location: drivers/gpio/gpiolib-cdev.c:1470
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl
```
**Symbols:**

```
ffffffff8194fcf0-ffffffff8194ffb3: linereq_set_config (STB_LOCAL)
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
