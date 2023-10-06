<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Busca de marcas</div>

                    <div class="card-body">
                        <div class="form row">
                            <div class="col mb-3">
                                <inputcontainer-component
                                    titulo="ID"
                                    id="inputId"
                                    idHelp="idHelp"
                                    textoAjuda="Opcional. Informe o ID da marca"
                                >
                                    <input
                                        type="number"
                                        class="form-control"
                                        id="inputId"
                                        placeholder="ID"
                                        aria-describedby="idHelp"
                                />
                                </inputcontainer-component>
                            </div>

                                <inputcontainer-component
                                    titulo="ID"
                                    id="inputId"
                                    idHelp="idHelp"
                                    textoAjuda="Opcional. Informe o ID da marca"
                                >
                                    <input
                                        type="number"
                                        class="form-control"
                                        id="inputId"
                                        placeholder="ID"
                                        aria-describedby="idHelp"
                                />
                                </inputcontainer-component>

                            <div class="col mb-3">
                                <label for="inputNome" class="form-label"
                                    >Nome</label
                                >
                                <input
                                    type="text"
                                    class="form-control"
                                    id="inputNome"
                                    placeholder="nome"
                                />
                                <div id="nomeHelp" class="form-text">
                                    Opcional. Informe o nome.
                                </div>
                            </div>

                            <div class="card-footer">
                                <button
                                    type="submit"
                                    class="btn btn-primary btn-sm float-end"
                                >
                                    Pesquisar
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import InputContainer from "./InputContainer.vue";
export default {
    components: { InputContainer },
};
</script>
