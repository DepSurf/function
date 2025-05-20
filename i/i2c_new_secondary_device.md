# Function: <code>i2c_new_secondary_device</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct i2c_client *i2c_new_secondary_device(struct i2c_client *client, const char *name, u16 default_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dd510)
Location: drivers/i2c/i2c-core.c:1309
Inline: False
```
**Symbols:**

```
ffffffff816dd510-ffffffff816dd561: i2c_new_secondary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct i2c_client *i2c_new_secondary_device(struct i2c_client *client, const char *name, u16 default_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170d890)
Location: drivers/i2c/i2c-core.c:1447
Inline: False
```
**Symbols:**

```
ffffffff8170d890-ffffffff8170d8e1: i2c_new_secondary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct i2c_client *i2c_new_secondary_device(struct i2c_client *client, const char *name, u16 default_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720e20)
Location: drivers/i2c/i2c-core-base.c:893
Inline: False
```
**Symbols:**

```
ffffffff81720e20-ffffffff81720e71: i2c_new_secondary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct i2c_client *i2c_new_secondary_device(struct i2c_client *client, const char *name, u16 default_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817921a0)
Location: drivers/i2c/i2c-core-base.c:910
Inline: False
```
**Symbols:**

```
ffffffff817921a0-ffffffff817921f1: i2c_new_secondary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct i2c_client *i2c_new_secondary_device(struct i2c_client *client, const char *name, u16 default_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d4bb0)
Location: drivers/i2c/i2c-core-base.c:889
Inline: False
```
**Symbols:**

```
ffffffff817d4bb0-ffffffff817d4c01: i2c_new_secondary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct i2c_client *i2c_new_secondary_device(struct i2c_client *client, const char *name, u16 default_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fbd00)
Location: drivers/i2c/i2c-core-base.c:901
Inline: False
```
**Symbols:**

```
ffffffff817fbd00-ffffffff817fbd51: i2c_new_secondary_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct i2c_client *i2c_new_secondary_device(struct i2c_client *client, const char *name, u16 default_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183d5c0)
Location: drivers/i2c/i2c-core-base.c:990
Inline: False
```
**Symbols:**

```
ffffffff8183d5c0-ffffffff8183d61f: i2c_new_secondary_device (STB_GLOBAL)
```
</details>
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
