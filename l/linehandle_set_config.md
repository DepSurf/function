# Function: <code>linehandle_set_config</code>

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
long int linehandle_set_config(struct linehandle_state *lh, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81611330)
Location: drivers/gpio/gpiolib.c:504
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff81611330-ffffffff81611585: linehandle_set_config (STB_LOCAL)
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
long int linehandle_set_config(struct linehandle_state *lh, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aabf0)
Location: drivers/gpio/gpiolib-cdev.c:151
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff817aabf0-ffffffff817aada1: linehandle_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int linehandle_set_config(struct linehandle_state *lh, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c39a0)
Location: drivers/gpio/gpiolib-cdev.c:197
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
**Symbols:**

```
ffffffff818c39a0-ffffffff818c3b51: linehandle_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int linehandle_set_config(struct linehandle_state *lh, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81906a70)
Location: drivers/gpio/gpiolib-cdev.c:197
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
**Symbols:**

```
ffffffff81906a70-ffffffff81906c21: linehandle_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int linehandle_set_config(struct linehandle_state *lh, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194e290)
Location: drivers/gpio/gpiolib-cdev.c:162
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
**Symbols:**

```
ffffffff8194e290-ffffffff8194e439: linehandle_set_config (STB_LOCAL)
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
