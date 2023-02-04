<script setup>
</script>

<template>
  <main>
    <section>
      <div class="inner-container">
        <h1>Styleguide</h1>

        <h2 class="h4">Headings</h2>
        <h1>Heading 1</h1>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <h4>Heading 4</h4>
        <h5>Heading 5</h5>
        <h6>Heading 6</h6>

        <Alert type="success" message="Success Alert" />
        <Alert type="error" message="Error Alert" />
        <Alert type="warning" message="Warning Alert" />
        <Alert message="Info Alert" />

        <div class="button-group">
          <div class="button">Primary Button</div>
          <div class="button secondary">Secondary Button</div>
        </div>
        <div class="button-group">
          <div class="button outline">Primary Button Outline</div>
          <div class="button secondary outline">Secondary Button Outline</div>
        </div>
        <div class="button-group">
          <div class="button no-border ">Primary Button Outline</div>
          <div class="button secondary no-border ">Secondary Button Outline</div>
        </div>

        <div class="button-group">
          <div class="button large">Large Button</div>
          <div class="button small">Small Button</div>
        </div>

        <div class="button-group">
          <div class="button icon icon-placeholder">
            <div class="icon-placeholder"></div>
          </div>

          <div class="button icon icon-left">
            <span class="icon-placeholder"></span>
            Icon Left
          </div>

          <div class="button icon icon-right">
            Icon Right
            <span class="icon-placeholder"></span>
          </div>
        </div>

        <h4>Input Fields</h4>

        <div class="field">
          <label>Input Field</label>
          <div class="input-wrap">
            <input type="text" class="input" />
          </div>
        </div>

        <div class="field">
          <label>Input Field (Hover)</label>
          <div class="input-wrap">
            <input type="text" class="input hover" />
          </div>
        </div>

        <div class="field">
          <label>Input Field (Focus)</label>
          <div class="input-wrap">
            <input type="text" class="input focus" />
          </div>
        </div>

        <div class="field">
          <label>Input Field (Readonly)</label>
          <div class="input-wrap">
            <input type="text" class="input" readonly />
          </div>
        </div>

        <div class="field">
          <label>Input Field (Disabled)</label>
          <div class="input-wrap">
            <input type="text" class="input" disabled />
          </div>
        </div>

        <div class="field no-label">
          <label>Input Field</label>
          <div class="input-wrap">
            <input type="text" class="input" />
          </div>
          <div class="extra">No Label - Exta Info</div>
        </div>

        <div class="field no-label">
          <label>Select Field</label>
          <div class="input-wrap select-wrap">
            <select class="input">
              <option>Option</option>
            </select>
          </div>
        </div>

        <div class="field no-label">
          <label>Select Field (No Border)</label>
          <div class="input-wrap select-wrap no-border">
            <select class="input">
              <option>Option</option>
            </select>
          </div>
        </div>

        <div class="field no-label">
          <label>Textarea</label>
          <div class="input-wrap">
            <textarea class="input"></textarea>
          </div>
        </div>

        <div class="field">
          <label>Input Field</label>
          <div class="input-wrap button-inline">
            <input type="text" class="input" />
            <button class="button">Button</button>
          </div>
        </div>

        <div class="field">
          <label>Radio Field</label>
          <div class="input-wrap radio-group">

            <div class="radio">
              <input type="radio" id="radio-1-1" name="radio-1" checked />
              <label for="radio-1-1">Radio 1-1</label>
            </div>

            <div class="radio">
              <input type="radio" id="radio-1-2" name="radio-1" />
              <label for="radio-1-2">Radio 1-2</label>
            </div>

            <div class="radio">
              <input type="radio" id="radio-1-3" name="radio-1" disabled />
              <label for="radio-1-3">Radio 1-3</label>
            </div>
          </div>
        </div>

        <div class="field">
          <label>Radio Field (Horizontal)</label>
          <div class="input-wrap radio-group horizontal">

            <div class="radio">
              <input type="radio" id="radio-2-1" name="radio-2" checked />
              <label for="radio-2-1">Radio 2-1</label>
            </div>

            <div class="radio">
              <input type="radio" id="radio-2-2" name="radio-2" />
              <label for="radio-2-2">Radio 2-2</label>
            </div>

            <div class="radio">
              <input type="radio" id="radio-2-3" name="radio-2" disabled />
              <label for="radio-2-3">Radio 2-3</label>
            </div>

          </div>
        </div>

        <div class="field">
          <label>Radio Field</label>
          <div class="input-wrap radio-group radio-buttons">

            <div class="radio">
              <input type="radio" id="radio-3-1" name="radio-3" checked />
              <label for="radio-3-1">Radio 3-1</label>
            </div>

            <div class="radio">
              <input type="radio" id="radio-3-2" name="radio-3" />
              <label for="radio-3-2">Radio 3-2</label>
            </div>

            <div class="radio">
              <input type="radio" id="radio-3-3" name="radio-3" disabled />
              <label for="radio-3-3">Radio 3-3</label>
            </div>
          </div>
        </div>

        <div class="field">
          <label>Radio Field (Horizontal)</label>
          <div class="input-wrap radio-group radio-buttons horizontal">

            <div class="radio">
              <input type="radio" id="radio-4-1" name="radio-4" checked />
              <label for="radio-4-1">Radio 4-1</label>
            </div>

            <div class="radio">
              <input type="radio" id="radio-4-2" name="radio-4" />
              <label for="radio-4-2">Radio 4-2</label>
            </div>

            <div class="radio">
              <input type="radio" id="radio-4-3" name="radio-4" disabled />
              <label for="radio-4-3">Radio 4-3</label>
            </div>

          </div>
        </div>

        <div class="field">
          <label>Checkbox Field</label>
          <div class="input-wrap checkbox-group">

            <div class="checkbox">
              <input type="checkbox" id="checkbox-1-1" name="checkbox-1[]" checked />
              <label for="checkbox-1-1">Checkbox 1-1</label>
            </div>

            <div class="checkbox">
              <input type="checkbox" id="checkbox-1-2" name="checkbox-1[]" />
              <label for="checkbox-1-2">Checkbox 1-2</label>
            </div>

            <div class="checkbox">
              <input type="checkbox" id="checkbox-1-3" name="checkbox-1[]" disabled />
              <label for="checkbox-1-3">Checkbox 1-3</label>
            </div>
          </div>
        </div>

        <div class="field">
          <label>Checkbox Fiel (Horizontal)</label>
          <div class="input-wrap checkbox-group horizontal">

            <div class="checkbox">
              <input type="checkbox" id="checkbox-2-1" name="checkbox-2[]" checked />
              <label for="checkbox-2-1">Checkbox 2-1</label>
            </div>

            <div class="checkbox">
              <input type="checkbox" id="checkbox-2-2" name="checkbox-2[]" />
              <label for="checkbox-2-2">Checkbox 2-2</label>
            </div>

            <div class="checkbox">
              <input type="checkbox" id="checkbox-2-3" name="checkbox-2[]" disabled />
              <label for="checkbox-2-3">Checkbox 2-3</label>
            </div>
          </div>
        </div>

        <div class="field">
          <label>Checkbox Switch</label>
          <div class="input-wrap checkbox-group horizontal">

            <div class="checkbox switch">
              <input type="checkbox" id="checkbox-3-1" name="checkbox-3[]" checked />
              <label for="checkbox-3-1"></label>
            </div>

            <div class="checkbox switch">
              <input type="checkbox" id="checkbox-4-1" name="checkbox-4[]" />
              <label for="checkbox-4-1"></label>
            </div>

            <div class="checkbox switch">
              <input type="checkbox" id="checkbox-5-1" name="checkbox-5[]" disabled />
              <label for="checkbox-5-1"></label>
            </div>
          </div>
        </div>


      </div>
    </section>
  </main>
</template>