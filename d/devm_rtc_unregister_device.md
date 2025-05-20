# Function: <code>devm_rtc_unregister_device</code>

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
void devm_rtc_unregister_device(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff8193ebf0)
Location: drivers/rtc/class.c:330
Inline: False
```
**Symbols:**

```
ffffffff8193ebf0-ffffffff8193ec3d: devm_rtc_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devm_rtc_unregister_device(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff819223e0)
Location: drivers/rtc/class.c:327
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff819223e0-ffffffff8192242d: devm_rtc_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_rtc_unregister_device(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff819c5390)
Location: drivers/rtc/class.c:327
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff819c5390-ffffffff819c53dd: devm_rtc_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_rtc_unregister_device(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81b25a20)
Location: drivers/rtc/class.c:337
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81b25a20-ffffffff81b25a84: devm_rtc_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_rtc_unregister_device(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81cb9010)
Location: drivers/rtc/class.c:337
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81cb9010-ffffffff81cb9074: devm_rtc_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_rtc_unregister_device(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81d20740)
Location: drivers/rtc/class.c:337
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81d20740-ffffffff81d207a4: devm_rtc_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_rtc_unregister_device(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81dd6470)
Location: drivers/rtc/class.c:337
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81dd6470-ffffffff81dd64d4: devm_rtc_unregister_device (STB_LOCAL)
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
