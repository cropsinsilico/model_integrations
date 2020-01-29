# model_integrations
A central location to store materials for model integrations that are publicly available.

## Cloning the repository

When cloning this repository be sure to include the `--recurse-submodules` flag to ensure that the models are cloned as submodules into the `model` directory. For example, to clone the repository without forking using https, you would use this command:

```
git clone --recurse-submodules https://github.com/cropsinsilico/model_integrations.git
```

## Updating the model submodules

To update the submodules with changes made to the model respositories, issue the following command:

```
git submodule update --remote
```

## Integrations

| Yaml                                                         | Description                                                                                        |
|--------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| ``C3-metabolic-and-leaf-model_ProtTranslationModel_CO2.yml`` | Integration of Yu Wang's C3 metabolic/leaf model and Kavya Kannan's protein translation model. |
