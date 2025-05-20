# Function: <code>devlink_flash_update_timeout_notify</code>

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
void devlink_flash_update_timeout_notify(struct devlink *devlink, const char *status_msg, const char *component, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a634a0)
Location: net/core/devlink.c:3434
Inline: False
```
**Symbols:**

```
ffffffff81a634a0-ffffffff81a634fc: devlink_flash_update_timeout_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_flash_update_timeout_notify(struct devlink *devlink, const char *status_msg, const char *component, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a473b0)
Location: net/core/devlink.c:3637
Inline: False
```
**Symbols:**

```
ffffffff81a473b0-ffffffff81a4740c: devlink_flash_update_timeout_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_flash_update_timeout_notify(struct devlink *devlink, const char *status_msg, const char *component, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afd2c0)
Location: net/core/devlink.c:4207
Inline: False
```
**Symbols:**

```
ffffffff81afd2c0-ffffffff81afd31c: devlink_flash_update_timeout_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_flash_update_timeout_notify(struct devlink *devlink, const char *status_msg, const char *component, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c802c0)
Location: net/core/devlink.c:4722
Inline: False
```
**Symbols:**

```
ffffffff81c802c0-ffffffff81c8032a: devlink_flash_update_timeout_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_flash_update_timeout_notify(struct devlink *devlink, const char *status_msg, const char *component, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e39470)
Location: net/core/devlink.c:4988
Inline: False
```
**Symbols:**

```
ffffffff81e39470-ffffffff81e394da: devlink_flash_update_timeout_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_flash_update_timeout_notify(struct devlink *devlink, const char *status_msg, const char *component, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82044310)
Location: net/devlink/dev.c:958
Inline: False
```
**Symbols:**

```
ffffffff82044310-ffffffff8204437a: devlink_flash_update_timeout_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_flash_update_timeout_notify(struct devlink *devlink, const char *status_msg, const char *component, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82103be0)
Location: net/devlink/dev.c:1059
Inline: False
```
**Symbols:**

```
ffffffff82103be0-ffffffff82103c4a: devlink_flash_update_timeout_notify (STB_GLOBAL)
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
