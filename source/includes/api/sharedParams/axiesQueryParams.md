### Query Parameters

Parameter | Default | Options | Description
--------- | ------- | ------- | ----------
lang      | en      | -       | Parameter for language data.
offset    | 0       | number  | Offset is used for pagination through filtered Axies, skipping amount of Axies set to offset and returning next batch of 12.
sale      | any     | 1       | Results will include Axies which are put on sale auction.
siring    | any     | 1       | Results will include Axies which are put on sire auction.
sorting   | highest_id | latest_auction, lowest_price, highest_price, lowest_id | Sorting criteria.
breedable | false   | yes     | If set to yes, results will include Axies, which are breedable.
stage     | any     | number <1, 4> | Stage of Axies, 1 - Egg, 2 - Larva, 3 - Petite, 4 - Adult.
class     | any     | beast, aquatic, plant, bird, bug, reptile, hidden_1, hidden_2, hidden_3 | Results will include Axies from specified class/classes.
region    | any     | japan   | Results will include Axies from specified region (which were birth with region option other than default).
title     | any     | origin, meo%20corp | Results will include Axies with specified tags.
mystic    | any     | true    | If set to true, results will include Mystic Axies.
num_mystic| any     | number <1, 6> | Results will include Axies which have specified number of Mystic parts.
pureness  | any     | number <1, 6> | Results will include Axies which have specified pureness of their parts.
part      | any     | string  | Results will include Axies which have specified parts, can be multiple.