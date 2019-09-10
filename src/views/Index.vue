<template>
  <section class="index">
    <section data-aos="fade-down" class="section contained mb-0">
      <div class="hero height-fill bg-primary bg-gradient txt-center">
        <h1 class="banger txt-huge txt-shadow">POW!</h1>
        <hr />
        <p>
          <em>The attention-seeking CSS framework</em>
        </p>
      </div>
    </section>
    <section data-aos="fade-down" class="section contained mt-0">
      <h1>Documentation</h1>
      <hr />
      <h2>Table of contents</h2>
      <ul>
        <li>Headers</li>
        <li>Paragraphs</li>
        <p class="mb-0">Buttons</p>
        <ul>
          <li>Regular</li>
          <li>Inverted</li>
          <li>Sizing</li>
        </ul>
      </ul>
    </section>
    <section data-aos="fade-down" class="section contained">
      <h2 id="headers">Headers</h2>
      <div class="hero p-1">
        <div class="h1">Header 1</div>
        <div class="h2">Header 2</div>
        <div class="h3">Header 3</div>
        <div class="h4">Header 4</div>
        <div class="h5">Header 5</div>
        <div class="h6">Header 6</div>
      </div>
    </section>
    <section data-aos="fade-down" class="section contained">
      <h2 id="paragraphs">Paragraphs</h2>
      <div class="hero p-1">
        <p>Regular paragraph</p>
        <p class="txt-huge">.txt-huge</p>
        <p class="txt-tiny">.txt-tiny</p>
        <p class="txt-shadow">.txt-shadow</p>
      </div>
    </section>
    <section data-aos="fade-down" class="section contained example">
      <h2 id="buttons">Buttons</h2>

      <div class="section section-sm p-0">
        <h3>Regular buttons</h3>

        <button class="btn">Default button</button>&nbsp;
        <button class="btn bg-primary">Primary button</button>&nbsp;
        <button class="btn bg-secondary">Secondary button</button>&nbsp;
        <button class="btn bg-success">Success button</button>&nbsp;
        <button class="btn bg-warning">Warning button</button>&nbsp;
        <button class="btn bg-error">Error button</button>&nbsp;
        <button class="btn bg-info">Info button</button>&nbsp;
        <button class="btn bg-dark">Dark button</button>&nbsp;
      </div>
      <div class="section section-sm p-0">
        <h3>Inverted buttons</h3>

        <button class="btn bg-invert bg-primary">Primary button</button>&nbsp;
        <button class="btn bg-invert bg-secondary">Secondary button</button
        >&nbsp;
        <button class="btn bg-invert bg-success">Success button</button>&nbsp;
        <button class="btn bg-invert bg-warning">Warning button</button>&nbsp;
        <button class="btn bg-invert bg-error">Error button</button>&nbsp;
        <button class="btn bg-invert bg-info">Info button</button>&nbsp;
        <button class="btn bg-invert bg-dark">Dark button</button>&nbsp;
      </div>

      <div class="section section-sm p-0">
        <h3>Sizing and rounding</h3>

        <button class="btn btn-sm bg-success">.btn.btn-sm</button>&nbsp;
        <button class="btn bg-success">.btn</button>&nbsp;
        <button class="btn btn-lg bg-success">.btn.btn-lg</button>&nbsp;
        <br /><br />
        <button class="btn bg-warning rounded">.btn.btn-rounded</button>&nbsp;
      </div>
    </section>
  </section>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style lang="scss">
.example {
  .btn {
    margin-bottom: 0.25rem;
  }
}
</style>
