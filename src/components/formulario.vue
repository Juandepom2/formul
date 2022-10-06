 
<template>
    <form>
        <div   class="form-group">
          <label for="exampleInputEmail1 " class=" form-label">proyecto</label>
          <input V-mode-trim="proyecto" type="text" class="form-control">
         </div>
         <br>
        <div class="form-group">
          <label  class="form-label"  >Actividad</label>
 <select  name="" id="">
    <option disabled value="">seleccione tipo de actividad....</option>
    <option value="1">aplicaciones web con vue.js</option>
    <option value="2">backend service con node.js</option>
    <option value="3">app movil con react native</option>

 </select>
        </div>
        <br>
        <div class="form-group form-check">
          <input  type="checkbox" class="form-check-input" id="exampleCheck1">
          <label class="form-check-label-input" >Urgente</label>
 
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
      <hr>
       
 
</template> 