# Function: <code>usb_role_switch_set_role</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch *sw, enum usb_role role);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8192b750)
Location: drivers/usb/roles/class.c:42
Inline: True
Direct callers:
  - drivers/usb/roles/class.c:role_store
```
**Symbols:**

```
ffffffff8192b750-ffffffff8192b7d5: usb_role_switch_set_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch *sw, enum usb_role role);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8190ecc0)
Location: drivers/usb/roles/class.c:42
Inline: True
Direct callers:
  - drivers/usb/roles/class.c:role_store
```
**Symbols:**

```
ffffffff8190ecc0-ffffffff8190ed45: usb_role_switch_set_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch *sw, enum usb_role role);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff819afb00)
Location: drivers/usb/roles/class.c:42
Inline: True
Direct callers:
  - drivers/usb/roles/class.c:role_store
```
**Symbols:**

```
ffffffff819afb00-ffffffff819afb85: usb_role_switch_set_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch *sw, enum usb_role role);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81b0e0b0)
Location: drivers/usb/roles/class.c:42
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:role_store
```
**Symbols:**

```
ffffffff81b0e0b0-ffffffff81b0e145: usb_role_switch_set_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch *sw, enum usb_role role);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81c9e1f0)
Location: drivers/usb/roles/class.c:42
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:role_store
```
**Symbols:**

```
ffffffff81c9e1f0-ffffffff81c9e285: usb_role_switch_set_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch *sw, enum usb_role role);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81d05550)
Location: drivers/usb/roles/class.c:44
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:role_store
```
**Symbols:**

```
ffffffff81d05550-ffffffff81d055e5: usb_role_switch_set_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch *sw, enum usb_role role);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:46
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:role_store
```
**Symbols:**

```
ffffffff82208c07-ffffffff82208c1c: usb_role_switch_set_role.cold (STB_LOCAL)
ffffffff81dbb430-ffffffff81dbb4e9: usb_role_switch_set_role (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch *sw, enum usb_role role);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (ffff800010a91740)
Location: drivers/usb/roles/class.c:42
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:role_store
Direct callers:
  - drivers/usb/roles/class.c:role_store
```
**Symbols:**

```
ffff800010a91638-ffff800010a9169c: usb_role_switch_set_role.part.0 (STB_LOCAL)
ffff800010a916a0-ffff800010a916f0: usb_role_switch_set_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch *sw, enum usb_role role);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (c0b74f3c)
Location: drivers/usb/roles/class.c:42
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:role_store
Direct callers:
  - drivers/usb/roles/class.c:role_store
```
**Symbols:**

```
c0b74e68-c0b74eb8: usb_role_switch_set_role.part.0 (STB_LOCAL)
c0b74eb8-c0b74eec: usb_role_switch_set_role (STB_GLOBAL)
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
