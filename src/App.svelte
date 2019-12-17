<script>
  import Header from "./components/header/Header.svelte";
  import LeftNavbar from "./components/navbar/LeftNavbar.svelte";
  import RightNavbar from "./components/navbar/RightNavbar.svelte";
  import Main from "./components/main/Main.svelte";
  import ExampleContent from "./ExampeContent.svelte";
  import Modal from "./components/modal/Modal.svelte";
</script>

<div id="root">
  <Header>
    <LeftNavbar />
    <!-- <RightNavbar /> -->
  </Header>
  <Main>
    <ExampleContent />
  </Main>
  <Modal />
</div>
