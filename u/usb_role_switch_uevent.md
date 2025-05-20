# Function: <code>usb_role_switch_uevent</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_role_switch_uevent(struct device *dev, struct kobj_uevent_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:264
Inline: False
```
**Symbols:**

```
ffffffff8192b6f0-ffffffff8192b72d: usb_role_switch_uevent (STB_LOCAL)
ffffffff81c2290a-ffffffff81c22924: usb_role_switch_uevent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_role_switch_uevent(struct device *dev, struct kobj_uevent_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:266
Inline: False
```
**Symbols:**

```
ffffffff8190ec60-ffffffff8190ec9d: usb_role_switch_uevent (STB_LOCAL)
ffffffff81c14b4b-ffffffff81c14b65: usb_role_switch_uevent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_role_switch_uevent(struct device *dev, struct kobj_uevent_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:275
Inline: False
```
**Symbols:**

```
ffffffff819afa60-ffffffff819afa9d: usb_role_switch_uevent (STB_LOCAL)
ffffffff81d2210b-ffffffff81d22125: usb_role_switch_uevent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_role_switch_uevent(struct device *dev, struct kobj_uevent_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:275
Inline: False
```
**Symbols:**

```
ffffffff81b0e3d0-ffffffff81b0e414: usb_role_switch_uevent (STB_LOCAL)
ffffffff81eedcdb-ffffffff81eedcf5: usb_role_switch_uevent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_role_switch_uevent(struct device *dev, struct kobj_uevent_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81c9e590)
Location: drivers/usb/roles/class.c:278
Inline: False
```
**Symbols:**

```
ffffffff81c9e590-ffffffff81c9e5f8: usb_role_switch_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_role_switch_uevent(const struct device *dev, struct kobj_uevent_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81d058d0)
Location: drivers/usb/roles/class.c:279
Inline: False
```
**Symbols:**

```
ffffffff81d058d0-ffffffff81d05938: usb_role_switch_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_role_switch_uevent(const struct device *dev, struct kobj_uevent_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81dbb360)
Location: drivers/usb/roles/class.c:287
Inline: False
```
**Symbols:**

```
ffffffff81dbb360-ffffffff81dbb3c8: usb_role_switch_uevent (STB_LOCAL)
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
int usb_role_switch_uevent(struct device *dev, struct kobj_uevent_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffff800010a91598)
Location: drivers/usb/roles/class.c:245
Inline: False
```
**Symbols:**

```
ffff800010a91598-ffff800010a915fc: usb_role_switch_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_role_switch_uevent(struct device *dev, struct kobj_uevent_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (c0b74de4)
Location: drivers/usb/roles/class.c:245
Inline: False
```
**Symbols:**

```
c0b74de4-c0b74e3c: usb_role_switch_uevent (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
