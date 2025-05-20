# Function: <code>devlink_info_board_serial_number_put</code>

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
int devlink_info_board_serial_number_put(struct devlink_info_req *req, const char *bsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5cc90)
Location: net/core/devlink.c:5072
Inline: False
```
**Symbols:**

```
ffffffff81a5cc90-ffffffff81a5ccc2: devlink_info_board_serial_number_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_info_board_serial_number_put(struct devlink_info_req *req, const char *bsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3f6d0)
Location: net/core/devlink.c:5275
Inline: False
```
**Symbols:**

```
ffffffff81a3f6d0-ffffffff81a3f702: devlink_info_board_serial_number_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_info_board_serial_number_put(struct devlink_info_req *req, const char *bsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af5ef0)
Location: net/core/devlink.c:5885
Inline: False
```
**Symbols:**

```
ffffffff81af5ef0-ffffffff81af5f22: devlink_info_board_serial_number_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_info_board_serial_number_put(struct devlink_info_req *req, const char *bsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c79c50)
Location: net/core/devlink.c:6380
Inline: False
```
**Symbols:**

```
ffffffff81c79c50-ffffffff81c79c8f: devlink_info_board_serial_number_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_info_board_serial_number_put(struct devlink_info_req *req, const char *bsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e32520)
Location: net/core/devlink.c:6892
Inline: False
```
**Symbols:**

```
ffffffff81e32520-ffffffff81e32565: devlink_info_board_serial_number_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_info_board_serial_number_put(struct devlink_info_req *req, const char *bsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82042f40)
Location: net/devlink/dev.c:657
Inline: False
```
**Symbols:**

```
ffffffff82042f40-ffffffff82042f85: devlink_info_board_serial_number_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_info_board_serial_number_put(struct devlink_info_req *req, const char *bsn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82102390)
Location: net/devlink/dev.c:758
Inline: False
```
**Symbols:**

```
ffffffff82102390-ffffffff821023d5: devlink_info_board_serial_number_put (STB_GLOBAL)
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
