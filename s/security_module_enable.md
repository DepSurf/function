# Function: <code>security_module_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_module_enable(const char *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81f982fc)
Location: security/security.c:94
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
**Symbols:**

```
ffffffff81f982fc-ffffffff81f98316: security_module_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_module_enable(const char *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81fc2f99)
Location: security/security.c:95
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
**Symbols:**

```
ffffffff81fc2f99-ffffffff81fc2fb3: security_module_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_module_enable(const char *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81fff9e5)
Location: security/security.c:95
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
```
**Symbols:**

```
ffffffff81fff9e5-ffffffff81fff9ff: security_module_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool security_module_enable(const char *lsm, const bool stacked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff820e2d00)
Location: security/security.c:228
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_init
```
**Symbols:**

```
ffffffff820e2d00-ffffffff820e2f1d: security_module_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool security_module_enable(const char *lsm, const bool stacked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff826eb969)
Location: security/security.c:243
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_init
```
**Symbols:**

```
ffffffff826eb969-ffffffff826ebb86: security_module_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_module_enable(const char *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82715e03)
Location: security/security.c:154
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_init
  - security/smack/smack_lsm.c:smack_init
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/apparmor/lsm.c:apparmor_init
```
**Symbols:**

```
ffffffff82715e03-ffffffff82715e22: security_module_enable (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *lsm</code>
</li>
<li>
<b>Param added. </b>
<code>const bool stacked</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *module</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *module</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *lsm</code>
</li>
<li>
<b>Param removed. </b>
<code>const bool stacked</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
