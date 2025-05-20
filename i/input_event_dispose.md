# Function: <code>input_event_dispose</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void input_event_dispose(struct input_dev *dev, int disposition, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81ca8136)
Location: drivers/input/input.c:348
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
Direct callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_suspend
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:inhibited_store
  - drivers/input/input.c:input_set_keycode
```
**Symbols:**

```
ffffffff81ca67e0-ffffffff81ca6953: input_event_dispose (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void input_event_dispose(struct input_dev *dev, int disposition, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81d0f646)
Location: drivers/input/input.c:351
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
Direct callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_suspend
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:inhibited_store
  - drivers/input/input.c:input_set_keycode
```
**Symbols:**

```
ffffffff81d0df20-ffffffff81d0e093: input_event_dispose (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void input_event_dispose(struct input_dev *dev, int disposition, unsigned int type, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81dc5246)
Location: drivers/input/input.c:351
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_keycode
Direct callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_suspend
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:inhibited_store
  - drivers/input/input.c:input_set_keycode
```
**Symbols:**

```
ffffffff81dc3b40-ffffffff81dc3cb3: input_event_dispose (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
