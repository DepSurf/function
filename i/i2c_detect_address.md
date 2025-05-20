# Function: <code>i2c_detect_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167d448)
Location: drivers/i2c/i2c-core.c:2381
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816de1db)
Location: drivers/i2c/i2c-core.c:2586
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170e59b)
Location: drivers/i2c/i2c-core.c:2873
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8172172b)
Location: drivers/i2c/i2c-core-base.c:2059
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81792a5b)
Location: drivers/i2c/i2c-core-base.c:2083
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d5723)
Location: drivers/i2c/i2c-core-base.c:2069
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fc782)
Location: drivers/i2c/i2c-core-base.c:2069
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183cd3c)
Location: drivers/i2c/i2c-core-base.c:2162
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186e73c)
Location: drivers/i2c/i2c-core-base.c:2167
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_detect_address(struct i2c_client *temp_client, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2097
Inline: False
```
**Symbols:**

```
ffffffff81942680-ffffffff819427d7: i2c_detect_address (STB_LOCAL)
ffffffff819434cb-ffffffff8194353e: i2c_detect_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_detect_address(struct i2c_client *temp_client, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2227
Inline: False
```
**Symbols:**

```
ffffffff819489f0-ffffffff81948b47: i2c_detect_address (STB_LOCAL)
ffffffff81c24b71-ffffffff81c24be4: i2c_detect_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_detect_address(struct i2c_client *temp_client, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2287
Inline: False
```
**Symbols:**

```
ffffffff8192c370-ffffffff8192c4c7: i2c_detect_address (STB_LOCAL)
ffffffff81c16c5d-ffffffff81c16cd0: i2c_detect_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_detect_address(struct i2c_client *temp_client, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2288
Inline: False
```
**Symbols:**

```
ffffffff819cf530-ffffffff819cf684: i2c_detect_address (STB_LOCAL)
ffffffff81d25942-ffffffff81d259b5: i2c_detect_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_detect_address(struct i2c_client *temp_client, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2291
Inline: False
```
**Symbols:**

```
ffffffff81b31320-ffffffff81b31490: i2c_detect_address (STB_LOCAL)
ffffffff81ef16ca-ffffffff81ef173f: i2c_detect_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_detect_address(struct i2c_client *temp_client, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5db0)
Location: drivers/i2c/i2c-core-base.c:2299
Inline: False
```
**Symbols:**

```
ffffffff81cc5db0-ffffffff81cc5f97: i2c_detect_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_detect_address(struct i2c_client *temp_client, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2da40)
Location: drivers/i2c/i2c-core-base.c:2412
Inline: False
```
**Symbols:**

```
ffffffff81d2da40-ffffffff81d2dc27: i2c_detect_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_detect_address(struct i2c_client *temp_client, struct i2c_driver *driver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de3980)
Location: drivers/i2c/i2c-core-base.c:2430
Inline: False
```
**Symbols:**

```
ffffffff81de3980-ffffffff81de3b67: i2c_detect_address (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab1e7c)
Location: drivers/i2c/i2c-core-base.c:2167
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b9353c)
Location: drivers/i2c/i2c-core-base.c:2167
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b95468)
Location: drivers/i2c/i2c-core-base.c:2167
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9bac)
Location: drivers/i2c/i2c-core-base.c:2167
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff818628cc)
Location: drivers/i2c/i2c-core-base.c:2167
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187db2c)
Location: drivers/i2c/i2c-core-base.c:2167
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
