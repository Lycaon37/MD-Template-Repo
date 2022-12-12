This is an example list of FDB changes one could make. Please edit this list suit your own changes.

- AnimalInterestRating:
  - NewBorn: from 0.25 to 0.45.
- DesiredGenderRatios:
  - MaxMalesSingle: from 8 to 12.
  - MaxMalesBoth: from 8 to 12.
- DesiredPopulationSizes:
  - MaxPopulation: from 8 to 12.
- FertilityData:
  - MinLitterSize: from 1 to 2.
  - MaxLitterSize: from 3 to 4.
- GuestAnimalDesire:
  - MaxDesiredPopulation: from 10 to 15.
  - SaturatedPopulation: from 15 to 25.
- SizeData:
  - MaxScaleMale: from 1.00 to 1.05.
  - MaxScaleFemale: from 1.00 to 1.05.

Definition of each FDB entry:
- AnimalInterestRating: How popular an animal is with guests. Minimum is 0.10. Maximum is 1.00.
- DesiredGenderRatios: Desired population of each gender in the habitat. This and DesiredPopulationSizes should match up.
- DesiredPopulationSizes: Desired minimum and maximum population of habitat. This and DesiredGenderRatios should match up.
- FertilityData: How many babies an animal can give birth to, gestation periods, etc.
- GuestAnimalDesire: How guests judge habitats based on population saturation. ("This animal looks lonely", "too crowded", etc.)
- SizeData: How large or small animals will be.

Thanks to the [PZ Modding Tutorial](https://docs.google.com/document/d/1Uzizbe_qvIxh0sbiDX9beHhTJp5Ad5XhnqaLacILqj0/edit#) for information on the entries.