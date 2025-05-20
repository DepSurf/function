# Function: <code>usb_role_switch_is_visible</code>

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
umode_t usb_role_switch_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8192b540)
Location: drivers/usb/roles/class.c:198
Inline: False
```
**Symbols:**

```
ffffffff8192b540-ffffffff8192b55c: usb_role_switch_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
umode_t usb_role_switch_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8190ea80)
Location: drivers/usb/roles/class.c:200
Inline: False
```
**Symbols:**

```
ffffffff8190ea80-ffffffff8190ea9c: usb_role_switch_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
umode_t usb_role_switch_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:200
Inline: False
```
**Symbols:**

```
ffffffff819afac0-ffffffff819afaf2: usb_role_switch_is_visible (STB_LOCAL)
ffffffff81d22125-ffffffff81d2213a: usb_role_switch_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
umode_t usb_role_switch_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:200
Inline: False
```
**Symbols:**

```
ffffffff81b0e450-ffffffff81b0e48a: usb_role_switch_is_visible (STB_LOCAL)
ffffffff81eedcf5-ffffffff81eedd0a: usb_role_switch_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
umode_t usb_role_switch_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:203
Inline: False
```
**Symbols:**

```
ffffffff81c9e650-ffffffff81c9e68a: usb_role_switch_is_visible (STB_LOCAL)
ffffffff820a5e91-ffffffff820a5ea6: usb_role_switch_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
umode_t usb_role_switch_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:205
Inline: False
```
**Symbols:**

```
ffffffff81d05990-ffffffff81d059ca: usb_role_switch_is_visible (STB_LOCAL)
ffffffff8212729b-ffffffff821272b0: usb_role_switch_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
umode_t usb_role_switch_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:213
Inline: False
```
**Symbols:**

```
ffffffff81dbb3e0-ffffffff81dbb41a: usb_role_switch_is_visible (STB_LOCAL)
ffffffff82208bf2-ffffffff82208c07: usb_role_switch_is_visible.cold (STB_LOCAL)
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
umode_t usb_role_switch_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffff800010a913f8)
Location: drivers/usb/roles/class.c:179
Inline: False
```
**Symbols:**

```
ffff800010a913f8-ffff800010a9143c: usb_role_switch_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
umode_t usb_role_switch_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (c0b74ca8)
Location: drivers/usb/roles/class.c:179
Inline: False
```
**Symbols:**

```
c0b74ca8-c0b74ccc: usb_role_switch_is_visible (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
